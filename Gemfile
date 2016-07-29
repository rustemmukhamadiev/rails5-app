source "https://rubygems.org"

ruby "2.3.1"

gem "rails", "~> 5.0.0"
gem "pg"

# assets
gem "coffee-rails"
gem "jquery-rails"
gem "sass-rails", "~> 5.0"
gem "therubyracer", platforms: :ruby
gem "uglifier", ">= 1.3.0"

# views
gem "slim"

# all other gems
gem "devise"
gem "puma", "~> 3.0"

group :test do
  gem "capybara"
  gem "capybara-webkit"
  gem "codeclimate-test-reporter", require: false
  gem "database_cleaner"
  gem "email_spec"
  gem "formulaic"
  gem "launchy"
  gem "rspec-its"
  gem "shoulda-matchers"
  gem "webmock", require: false
end

group :development, :test do
  gem "brakeman", require: false
  gem "bundler-audit", require: false
  gem "factory_girl_rails"
  gem "faker"
  gem "byebug", platform: :mri
  gem "jasmine", "> 2.0"
  gem "jasmine-jquery-rails"
  gem "rspec-rails", "~> 3.4"
  gem "rubocop", require: false
  gem "rubocop-rspec", require: false
  gem "scss_lint", require: false
  gem "slim_lint", require: false
end

group :development do
  gem "listen", "~> 3.0.5"
  gem "slim-rails"
  gem "spring"
  gem "spring-commands-rspec"
  gem "web-console"
end
