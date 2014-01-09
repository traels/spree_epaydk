source 'https://rubygems.org'

# Provides basic authentication functionality for testing parts of your engine
gem 'spree_auth_devise', github: 'spree/spree_auth_devise', branch: '2-1-stable'
gem 'spree_gateway', github: 'spree/spree_gateway', branch: '2-1-stable'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby
  gem 'uglifier', '>= 1.0.3'
end

gem 'rspec-rails'
group :test do
  gem 'capybara'
  gem 'capybara-screenshot', :require => false
  gem 'selenium-webdriver'
  gem 'poltergeist'
  gem 'factory_girl_rails'
  gem 'database_cleaner'
end

gemspec
