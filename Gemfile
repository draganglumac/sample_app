source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'bootstrap-sass', '2.0.0'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'
group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
end

group :test do
  gem 'capybara'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

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

group :production do
  gem 'pg'
end

# IMPORTANT! Some of the defaults have changed in Capybara 2.1. If you're experiencing failures,
# please revert to the old behaviour by setting:
# 
#     Capybara.configure do |config|
#       config.match = :one
#       config.exact_options = true
#       config.ignore_hidden_elements = true
#       config.visible_text_only = true
#     end
# 
# If you're migrating from Capybara 1.x, try:
# 
#     Capybara.configure do |config|
#       config.match = :prefer_exact
#       config.ignore_hidden_elements = false
#     end
# 
# Details here: http://www.elabs.se/blog/60-introducing-capybara-2-1
