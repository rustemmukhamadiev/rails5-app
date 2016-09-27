source "https://rubygems.org"

ruby "2.3.1"

gem "rails", "~> 5.0.0"
gem "pg"

# assets
gem "activemodel-serializers-xml", git: "https://github.com/rails/activemodel-serializers-xml.git"
gem "coffee-rails"
gem "foundation-icons-sass-rails"
gem "foundation-rails", "= 5.5.2.1"
gem "jquery-rails"
gem "sass-rails", "~> 5.0.3"
gem "therubyracer", platforms: :ruby
gem "uglifier", ">= 1.3.0"

# views
gem "active_link_to"
gem "metamagic"
gem "simple_form", git: "https://github.com/kesha-antonov/simple_form.git", branch: "rails-5-0"
gem "slim"

# all other gems
gem "decent_decoration"
gem "decent_exposure"
gem "devise"
gem "draper", git: "https://github.com/audionerd/draper.git", branch: "rails5"
gem "google-analytics-rails"
gem "interactor"
gem "kaminari"
gem "puma", "~> 3.0"
gem "rack-canonical-host"
gem "rack-mini-profiler", require: false
gem "pundit"
gem "responders"
gem "rollbar"

group :staging, :production do
  gem "newrelic_rpm"
  gem "rails_stdout_logging"
end

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
