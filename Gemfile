source "http://rubygems.org"

gem "rails", "3.2.11"

gem 'will_paginate'

group 'test' do
  gem 'capybara-webkit'
  gem "factory_girl_rails"
  gem "sqlite3"
  gem "mocha"
  gem 'launchy'
end

group 'development' do
  if RUBY_VERSION < '1.9'
    gem "ruby-debug", ">= 0.10.3"
  end
end