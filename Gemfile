source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.2', '>= 6.0.2.1'
# a Ruby processor for ImageMagick
gem 'image_processing', '1.9.3'
gem 'mini_magick', '4.9.5'
# Active Storage (somewhat surprisingly) doesn’t offer native support for things like format and size validations, but as is so often the case there is a gem that adds it for us
gem 'active_storage_validations', '0.8.2'
# By hashing the password with bcrypt, we ensure that an attacker won’t be able to log in to the site even if they manage to obtain a copy of the database.
gem 'bcrypt', '3.1.13'
# add the Faker gem to the Gemfile , which will allow us to make sample users with semi-realistic names and email addresses
gem 'faker', '2.1.2'
# one of the simplest and most robust pagination method
gem 'will_paginate', '3.1.8'
# configures will_paginate to use Bootstrap’s pagination styles
gem 'bootstrap-will_paginate', '1.0.0'
# Bootstrap
gem 'bootstrap-sass', '3.4.1'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# assert_template has been extracted to a gem. To continue using it:
gem 'rails-controller-testing'

# Capistrano
gem 'capistrano', '~> 3.11'
gem 'capistrano-rails', '~> 1.4'
gem 'capistrano-passenger', '~> 0.2.0'
gem 'capistrano-rbenv', '~> 2.1', '>= 2.1.4'

# MimeMagic
gem 'mimemagic', '0.4.3'

group :development, :test do
  gem 'sqlite3', '1.4.1'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

group :production do
  gem 'pg', '1.1.4'
  # file storage on Heroku is temporary, use a cloud storage service to store images separately from our application
  # gem 'aws-sdk-s3', '1.46.0', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
