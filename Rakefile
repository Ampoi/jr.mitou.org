task default: 'test'

desc 'Check JSON format'
task :check_json_format do
  ruby "tests/check_json_format.rb"
end

# Upsert individual project page by data
desc 'Upsert project page by project data'
task :upsert_project_pages_by_data do
  ruby "tasks/upsert_project_pages_by_data.rb"
end

# cf. GitHub - gjtorikian/html-proofer
# https://github.com/gjtorikian/html-proofer

require 'html-proofer'
task test: [:build] do
  options = {
    checks: ['Links', 'Images', 'Scripts', 'OpenGraph', 'Favicon', 'Jsons'],
    allow_hash_href:  true,
    disable_external: ENV['TEST_EXTERNAL_LINKS'] != 'true',
    enforce_https:    true,

    # NOTE: Ignore file, URL, and response as follows
    ignore_files: [
      /google(.*)\.html/,
    ],
    ignore_urls: [
      'http://www.ecomaki.com/', # URL should be perfect-matching
      %r{^http://iql-lab.de},    # Use REGEX to ignore URLs in a domain
      %r{^http://nhiro.org},
      %r{^https://twitter.com},  # Skip testing Twitter URLs
    ],
    #ignore_status_codes: [0, 500, 999],
  }

  HTMLProofer.check_directory('_site', options).run
end

# Enable 'build' to flush cache files via 'clean'
task build: [:clean] do
  system 'JEKYLL_ENV=test bundle exec jekyll build' unless ENV['SKIP_BUILD'] == 'true'
end

task :clean do
  system 'bundle exec jekyll clean' unless ENV['SKIP_BUILD'] == 'true'
end
