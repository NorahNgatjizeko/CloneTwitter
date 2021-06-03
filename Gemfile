source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Core
gem 'rails', '~> 6.1.3', '>= 6.1.3.2'
# Config
gem 'dotenv-rails', '~> 2.2'
gem 'rails-i18n'
gem 'config'
#Middleware
gem 'puma', '~> 5.0'
gem 'pg', '~> 1.1'
#View/Front
gem 'webpacker', '~> 5.0'
gem 'coffee-rails', '~> 5.0'
gem 'jquery-rails'
gem 'haml-rails', '~> 2.0', '>= 2.0.1'
gem 'sass-rails', '>= 6'
# Backend
gem 'devise'
gem 'jbuilder', '~> 2.7'
gem 'enumerize'
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-github'
gem 'carrierwave'
gem 'cloudinary'
gem 'gon'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  gem 'spring'
end

group :test do

  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'

  gem 'webdrivers'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
