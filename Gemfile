source "https://rubygems.org"

# Specify your gem"s dependencies in react_on_rails.gemspec
gemspec

# The following gems are dependencies of the gem's dummy/example apps, not the gem itself.
# They must be defined here because of the way Travis CI works, in that it will only
# bundle install from a single Gemfile. Therefore, all gems that we will need for any dummy/example
# app have to be manually added to this file.
gem "bootstrap-sass"
gem "coffee-rails", "~> 4.1.0"
gem "jbuilder", "~> 2.0"
gem "jquery-rails"
gem "puma"
gem "rails", "4.2.8"
gem "rails_12factor"
gem "rubocop", require: false
gem "ruby-lint", require: false
gem "sass-rails", "~> 5.0"
gem "scss_lint", require: false
gem "sdoc", "~> 0.4.0", group: :doc
gem "spring"
gem "sqlite3"
gem "mini_racer"
if ENV["ENABLE_TURBOLINKS_5"].nil? || ENV["ENABLE_TURBOLINKS_5"].strip.empty?
  gem "turbolinks", "2.5.3"
else
  gem "turbolinks", "~> 5.0"
end
gem "uglifier", ">= 2.7.2"
gem "web-console", "~> 2.0", group: :development

# below are copied from spec/dummy/Gemfile
gem "rspec-rails"
gem "rspec-retry"
gem "capybara"
gem "capybara-screenshot"
gem "capybara-webkit"
gem "chromedriver-helper"
gem "launchy"
gem "poltergeist"
gem "selenium-webdriver"
