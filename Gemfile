source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails', '3.2.8'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'locomotive_cms', '~> 2.0.0.rc12', :require => 'locomotive/engine'

# Fixes bundler issue, which does not allow to perform bundle install
gem 'devise', '2.1.2'

gem 'locomotive-heroku', '~> 0.0.2', :require => 'locomotive/heroku'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',    '~> 3.2.3'
  gem 'coffee-rails',  '~> 3.2.1'
  gem 'compass-rails', '~> 1.0.2'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'unicorn'
end

group :production do
  gem 'thin'
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
