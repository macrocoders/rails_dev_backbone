source "https://rubygems.org"

ruby "2.2.3"

gem "puma", "~> 3.0"

group :development, :test do
  gem "byebug", platform: :mri
  gem "dotenv-rails"

  # code quality tools
  gem "brakeman", require: false
  gem "bundler-audit", require: false
  gem "coffeelint"
  gem "rubocop", require: false
  gem "rubocop-rspec", require: false
  gem "scss_lint", require: false
  gem "slim_lint", require: false

  # mostly testing gems
  gem "factory_girl_rails"
  gem "faker"
  gem "jasmine", "> 2.0"
  gem "jasmine-jquery-rails"
  gem "pry-rails"
  gem "rspec-rails", "~> 3.4"
end

group :test do
  gem "capybara"
  gem "capybara-webkit"
  gem "database_cleaner"
  gem "formulaic"
  gem "launchy"
  gem "rspec-its"
  gem "shoulda-matchers"
  gem "webmock", require: false
end

group :development do
  # N+1 queries detector
  gem "bullet"
  gem "web-console"
  # open emails locally in the browser
  gem "letter_opener"
  gem "listen", "~> 3.0.5"
  gem "foreman", require: false
  gem "slim-rails"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end
