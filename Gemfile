source "https://rubygems.org"

ruby "~> 3.0"

group :preload, :default do
  gem "rails", "~> 7.0.2"
  gem "bootsnap", ">= 1.1.0", require: false
  gem "falcon"
  gem "webpacker", "~> 5.4"
  gem "redis", "~> 4.6"
  gem "hiredis"

  gem "elasticsearch-persistence"

  gem "http"
  gem "typhoeus", require: false
  gem "kaminari", "~> 1.2.2"
  gem "inline_svg"
  gem "tty-spinner", require: false
  gem "skylight", group: :production
  gem "graphql"
  gem "graphiql-rails", group: :development
  gem "lograge"
  gem "logstash-event"
  gem "aws-sdk-s3"
  gem "sitemap_generator"
  gem "meta-tags"
  gem "sentry-ruby"
  gem "sentry-rails"
  gem "rack-attack"
  gem "rdoc", require: false
  gem "trenni-sanitize", require: false
  gem "pastel", require: false
  gem "rouge", require: false
end

gem "slim"

group :development, :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "dotenv-rails"
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", ">= 3.0.5", "< 3.8"
  gem "standard"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "webmock"
end
