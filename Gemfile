# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.1.2'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.4', '>= 7.0.4.1'

# The original asset pipeline for Rails
gem 'sprockets-rails'

# Use mysql as the database for Active Record
gem 'mysql2', '~> 0.5'

# Use the Puma web server
gem 'puma', '~> 5.0'

# Use JavaScript with ESM import maps
gem 'importmap-rails'

# Hotwire's SPA-like page accelerator
gem 'turbo-rails'

# Hotwire's modest JavaScript framework
gem 'stimulus-rails'

# Build JSON APIs with ease
gem 'jbuilder'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Use Kredis to get higher-level data types in Redis
gem 'kredis'

# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Use Sass to process CSS
gem 'sassc-rails'

# Use Active Storage variants
gem 'image_processing', '~> 1.2'

group :development, :test do
  # debug
  gem 'debug', platforms: %i[mri mingw x64_mingw]

  # Use console on exceptions pages
  gem 'web-console'

  # Use Factory bot
  gem 'factory_bot_rails'

  # Use Faker
  gem 'faker'

  # Use Rspec
  gem 'rspec-rails', '~> 6.0.1'

  # Use check codes
  gem 'rubocop'
  gem 'rubocop-rspec', require: false

  # spec coverage
  gem 'simplecov', require: false

  # security
  gem 'brakeman'

  # Use system testing
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end
