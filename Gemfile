source 'https://rubygems.org'

gem 'rails', '3.2.8'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  #gem 'sass-rails',   '~> 3.2.3'
  #gem 'coffee-rails', '~> 3.2.1'
  gem 'stylus', '~> 0.4.0'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

gem 'slim', '~> 1.1.0'
gem 'slim-rails', '~> 1.0.1'
gem 'heroku'

group :development do
  gem 'sqlite3'
end

group :production, :staging do
  gem 'pg'
end

group :test, :development do
  gem 'database_cleaner'
  gem 'rails3-generators'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'launchy'
  gem 'email_spec'
  gem 'shoulda-matchers'
  gem 'simplecov'
  gem 'pry-rails'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
