source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.3"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.3"
gem 'bootstrap', '~> 5.1.3'
gem 'jquery-rails'
gem 'bcrypt', '3.1.15'
gem 'will_paginate', '~> 3.3'


gem 'active_storage_validations', '0.8.2'
gem 'image_processing','1.12.2'
gem 'mini_magick','4.9.5'

gem 'faker'


gem 'chartjs-ror'
gem 'wicked_pdf'
gem 'wkhtmltopdf-binary'
gem 'spreadsheet'
gem 'mimemagic', github: 'mimemagicrb/mimemagic'

group :production do
   gem 'pg',         '1.1.4'
end


# The original asset pipeline for Rails [https://github.com/rails/sprockets-rails]
gem "sprockets-rails"



# Use the Puma web server [https://github.com/puma/puma]
gem "puma", "~> 5.0"

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
  #gem 'capistrano-cookbook',github: 'TCnet/capistrano-cookbook', require: false
  gem 'capistrano-cookbook', require: false, group: :development
  # Add speed badges [https://github.com/MiniProfiler/rack-mini-profiler]
  # gem "rack-mini-profiler"
  # Use sqlite3 as the database for Active Record
  gem "sqlite3", "~> 1.4"
  gem 'capistrano-rbenv', "~> 2.0"
  gem 'capistrano-rails'
  gem 'capistrano-bundler'

  # Speed up commands on slow machines / big apps [https://github.com/rails/spring]
  # gem "spring"
end

group :test do
  # Use system testing [https://guides.rubyonrails.org/testing.html#system-testing]
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
