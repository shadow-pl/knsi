source 'http://rubygems.org'

# Base framework
gem 'rails'

# Database support
gem 'mysql2'

# Model annotations
gem 'annotate'

# Authentication with Devise
gem 'warden'
gem 'devise'

# Authorization with CanCan
gem 'cancan'

# Unicorn server for *nix systems
if RUBY_PLATFORM !~ /(win|w)32/
  gem 'unicorn'
end

# Test enviroment setup
group :test, :development do
  gem 'autotest'
  gem 'rspec'
  gem "rspec-rails"
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
end
