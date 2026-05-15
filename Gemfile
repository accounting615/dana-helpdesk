source "https://rubygems.org"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 8.1.2"

# The modern asset pipeline for Rails
gem "propshaft"

# Use MariaDB / MySQL as the database for Active Record
gem "mysql2"

# Use the Puma web server
gem "puma", ">= 5.0"

# Use JavaScript with ESM import maps
gem "importmap-rails"

# Hotwire's SPA-like page accelerator
gem "turbo-rails"

# Hotwire's modest JavaScript framework
gem "stimulus-rails"

# Bundle and process CSS
gem "cssbundling-rails"

# Build JSON APIs with ease
gem "jbuilder", require: false

# Use Active Model has_secure_password
gem "bcrypt", "~> 3.1.21"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ windows jruby ]

# Use the database-backed adapters for Rails.cache, Active Job, and Action Cable
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Deploy this application anywhere as a Docker container
gem "kamal", require: false

# Add HTTP asset caching/compression and X-Sendfile acceleration to Puma
gem "thruster", require: false

# Use Active Storage variants
# gem "image_processing", "~> 1.2"

# Add authorization to your Rails application
gem "pundit", "~> 2.2"

# Add admin interface to your Rails application
gem "rails_admin", "~> 3.0"

# Adds pagination to your Rails application
gem "kaminari"

# Add user authentication to your Rails application
gem "devise", "~> 5.0"
gem "devise_invitable", "~> 2.0"

gem "dotenv", "~> 3.1"
gem "redcarpet", "~> 3.6"

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: %i[mri windows], require: "debug/prelude"

  # Static analysis for security vulnerabilities
  gem "brakeman", require: false

  # Omakase Ruby styling
  gem "rubocop-rails-omakase", require: false

  # Use letter_opener to preview emails in development
  gem "letter_opener"

  # Annotate models, routes, and components
  gem "annotate"

  # Use RSpec for testing
  gem "rspec-rails"
  gem "rubocop-rspec"
  gem "factory_bot_rails"

  # Debugging tool
  gem "byebug"

  # N+1 query detection
  gem "bullet"
end

group :development do
  # Use console on exceptions pages
  gem "web-console"

  gem "ruby-lsp-rspec", require: false

  # Profiling tools
  gem "rack-mini-profiler", require: false
  gem "memory_profiler"
  gem "stackprof"
end

group :test do
  # Use system testing
  gem "capybara"
  gem "selenium-webdriver"
end