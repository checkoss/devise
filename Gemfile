# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "rails", "~> 6.0.3", ">= 6.0.3.4"
gem "omniauth", ">= 1.9.2"
gem "omniauth-oauth2", ">= 1.7.1"
gem "rdoc"

gem "activemodel-serializers-xml", github: "rails/activemodel-serializers-xml"

gem "rails-controller-testing", github: "rails/rails-controller-testing"

gem "responders", "~> 3.1", ">= 3.1.0"

group :test do
  gem "omniauth-facebook", ">= 8.0.0"
  gem "omniauth-openid", ">= 2.0.1"
  gem "timecop"
  gem "webrat", "0.7.3", require: false
  gem "mocha", "~> 1.1", require: false
end

platforms :ruby do
  gem "sqlite3", "~> 1.4"
end

# platforms :jruby do
#   gem "activerecord-jdbc-adapter"
#   gem "activerecord-jdbcsqlite3-adapter"
#   gem "jruby-openssl"
# end

# TODO:
# group :mongoid do
#   gem "mongoid", "~> 4.0.0"
# end
