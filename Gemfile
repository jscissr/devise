# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "rails", "~> 6.0.0"
gem "omniauth"
gem "omniauth-oauth2"
gem "rdoc"

gem "activemodel-serializers-xml", github: "rails/activemodel-serializers-xml"

gem "rails-controller-testing", github: "rails/rails-controller-testing"

gem "responders", "~> 3.0"

group :test do
  gem "omniauth-facebook"
  gem "omniauth-openid", git: 'https://github.com/jkowens/omniauth-openid', branch: 'patch-1'
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
