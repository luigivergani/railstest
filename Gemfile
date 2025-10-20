source 'https://rubygems.org'

ruby '3.3.6'

gem 'rails', '~> 7.2.0'

# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'

# Use the Puma web server
gem 'puma', '~> 6.0'

# Use JavaScript with ESM import maps
gem 'importmap-rails'

# Hotwire's SPA-like page accelerator
gem 'turbo-rails'

# Hotwire's modest JavaScript framework
gem 'stimulus-rails'

# Build JSON APIs with ease
gem 'jbuilder'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 5.0'

# Use Kredis to get higher-level data types in Redis
# gem 'kredis'

# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[ windows jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', require: false

# Use Active Storage variants
# gem 'image_processing', '~> 1.2'

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem 'debug', platforms: %i[ mri windows ]
end

group :development do
  # Use console on exceptions pages
  gem 'web-console'

  # Add speed badges
  # gem 'rack-mini-profiler'

  # Speed up commands on slow machines / big apps
  # gem 'spring'
end

group :test do
  # Use system testing
  gem 'capybara'
  gem 'selenium-webdriver'
end

# Asset pipeline
gem 'sprockets-rails'
