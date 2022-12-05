source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.0.4"

gem "cancancan"
gem "config"
gem "devise"
gem "dry-initializer"
gem "dry-monads"
gem "dry-transaction"
# gem "exception_notification"
# gem "faraday"
gem "sprockets-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
# gem "rack-utf8_sanitizer"
gem "rails-i18n"
# gem "redis"
# gem "resque"
# gem "resque-scheduler"
# gem "rest-client"
# gem 'whenever', require: false

# Use JavaScript with ESM import maps [https://github.com/rails/importmap-rails]
gem "importmap-rails"

# Hotwire's SPA-like page accelerator [https://turbo.hotwired.dev]
gem "turbo-rails"

# Hotwire's modest JavaScript framework [https://stimulus.hotwired.dev]
gem "stimulus-rails"

# Build JSON APIs with ease [https://github.com/rails/jbuilder]
gem "jbuilder"

# Use Redis adapter to run Action Cable in production
# gem "redis", "~> 4.0"

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "rspec-rails", "~> 6.0.0"
  # gem "rubocop"
  # gem "rubocop-performance"
  # gem "rubocop-rails"
  # gem "rubocop-rspec"
  gem "webmock"
end

group :development do
  gem "web-console"
end

group :test do
  gem "factory_bot"
  gem "simplecov", require: false
end
