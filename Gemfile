# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.5'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'braintree', '~> 4.7'
gem 'devise', '~> 4.2'
gem 'figaro', '~> 1.2'
gem 'friendly_id', '~> 5.4'
gem 'image_processing', '~> 1.2'
gem 'jbuilder', '~> 2.7'
gem 'omniauth', '~> 2.1'
gem 'omniauth-github', '~> 2.0'
gem 'omniauth-google-oauth2', '~> 1.0', '>= 1.0.1'
gem 'omniauth-rails_csrf_protection', '~> 1.0', '>= 1.0.1'
gem 'paranoia', '~> 2.6'
gem 'pg', '1.3.5'
gem 'puma', '~> 5.0'
gem 'pundit', '~> 2.2'
gem 'rails', '6.1.5.1'
gem 'rails-i18n', '~> 7.0', '>= 7.0.3'
gem 'rubocop', '~> 1.29', require: false
gem 'sass-rails', '>= 6'
gem 'stimulus-rails', '~> 1.0', '>= 1.0.4'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 5.0'

group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'capybara', '~> 3.36'
  gem 'dotenv-rails', '~> 2.7', require: 'dotenv/rails-now'
  gem 'factory_bot_rails', '~> 6.2'
  gem 'faker', '~> 2.20'
  gem 'rspec-rails', '~> 5.1'
end

group :development do
  gem 'foreman', '~> 0.87.2'
  gem 'web-console', '>= 4.1.0'
  gem 'listen', '~> 3.3'
end

group :test do
  gem 'selenium-webdriver', '>= 4.0.0.rc1'
  gem 'webdrivers', '~> 5.0'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
