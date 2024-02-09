# frozen_string_literal: true

source "https://rubygems.org"

gem "active_record_union"
gem "base32"
gem "devise", ">= 4.7.1"
gem "font-awesome-rails"
gem "grape"
gem "grape-entity"
gem "grape-swagger"
gem "grape-swagger-entity"
gem "gravatar_image_tag"
gem "hashie-forbidden_attributes"
gem "jwt"
gem "kaminari", ">= 1.2.1"
gem "net-ldap"
gem "omniauth-github", ">= 2.0.0"
gem "omniauth-gitlab", ">= 3.0.0"
gem "omniauth-google-oauth2", ">= 0.7.0"
gem "omniauth-openid", ">= 2.0.1"
gem "omniauth_openid_connect", ">= 0.4.0"
gem "public_activity", "~> 1.6.3"
gem "pundit"
gem "rails", "~> 6.1.7", ">= 6.1.7.3"
gem "redcarpet", ">= 3.5.1"
gem "sassc-rails"
gem "search_cop"
gem "slim"
gem "webpack-rails"

gem "rack-cors", ">= 1.0.5"

# Supported DBs
gem "mysql2", group: :db
gem "pg", group: :db

# Pinning these specific versions because that's what we have on OBS.
gem "ethon"
gem "typhoeus"

# Used to store application tokens.
gem "bcrypt"

# If the deployment is done through Puma, include it in the bundle.
gem "puma", ">= 5.6.7"

# Configuration management
gem "cconfig", "~> 1.2.0"

# Pinning some versions
gem "i18n"
gem "ice_nine"
gem "minitest"
gem "multi_json"
gem "rails-dom-testing"
gem "sprockets"
gem "sprockets-rails"
gem "temple"

##
# The following groups will *not* be included on the production installation.

group :assets do
  gem "bootstrap-sass"
  gem "uglifier"
end

group :development do
  gem "annotate"
  gem "git-review", require: false
  gem "guard", require: false
  gem "guard-rspec", require: false
  gem "guard-rubocop", require: false
  gem "pry-rails"
  gem "rack-mini-profiler", require: false
  gem "rails-erd"
  gem "web-console"
end

group :development, :test do
  gem "rspec-core"
  gem "rspec-rails"

  gem "awesome_print"
  gem "binman"
  gem "brakeman", require: false
  gem "byebug"
  gem "database_cleaner"
  gem "factory_bot_rails"
  gem "ffaker"
  gem "grape-swagger-rails"
  gem "hirb"
  gem "rubocop", require: false
  gem "wirb"
  gem "wirble"
end

group :test do
  gem "capybara"
  gem "capybara-screenshot"
  gem "chromedriver-helper"
  gem "docker-api", ">= 2.0.0"
  gem "json-schema"
  gem "poltergeist", require: false
  gem "rails-controller-testing"
  gem "selenium-webdriver", ">= 3.142.0"
  gem "shoulda"
  gem "simplecov", ">= 0.17.0", require: false
  gem "timecop"
  gem "vcr"
  gem "webmock", require: false
end
