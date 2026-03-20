source 'https://rubygems.org'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.5"

gem 'ffi'

gem 'sass-rails'
gem 'uglifier'

gem 'jquery-rails'
gem 'bigdecimal'
gem 'web-console'

# for Heroku deployment - as described in Ap. A of ELLS book
group :development, :test do
  gem 'byebug'
  gem 'database_cleaner'
  gem 'cucumber-rails', require: false
  gem 'rspec-rails'
  gem 'pry'
  gem 'pry-byebug'
  gem 'faraday'
  gem 'guard'
  gem 'guard-rspec', require: false

  # Use sqlite3 as the database for Active Record
  gem "sqlite3", ">= 1.4"
end

group :production do
  gem "pg", "~> 1.6"
  gem 'rails_12factor'
end
