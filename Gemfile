# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'jbuilder', '~> 2.7'
gem 'puma', '~> 5.0'
gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 5.0'

gem 'pg'
gem 'pg_search'
gem 'redis'
gem 'sidekiq'
gem 'sidekiq-scheduler'
# gem 'mongoid', '~> 7.0.5'

gem 'clearance'
gem 'money-rails'
gem 'slim-rails'
gem 'twilio-ruby'

gem 'asset_sync'
gem 'aws-sdk-s3', require: false
gem 'fog-aws'
gem 'image_processing', '>= 1.2'

gem 'google-analytics-rails', '1.1.1'
gem 'newrelic_rpm'
gem 'airbrake'
gem 'ddtrace', require: 'ddtrace/auto_instrument'
gem 'lograge'
gem 'lograge-sql'

group :development, :test do
  gem 'break'
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'dotenv-rails'
  gem 'pry'
end

group :development do
  gem 'annotate'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'letter_opener'
  gem 'listen', '~> 3.3'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'rubocop', '~> 1.22', require: false
  gem 'rubocop-rails'
  gem 'spring'
  gem 'web-console', '>= 4.1.0'
end

group :development do
  gem 'capistrano',         require: false
  gem 'capistrano3-puma',   require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-rails',   require: false
  gem 'capistrano-rbenv',   require: false
  gem 'capistrano-rails-logs-tail',   require: false
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
