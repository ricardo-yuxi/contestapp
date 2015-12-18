source 'https://rubygems.org'

gem 'rails', '4.2.4'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

# Shopify
gem 'execjs'
gem 'twitter-bootstrap-rails'
gem 'bootstrap-sass'

group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
  # Helpful gems
  gem 'better_errors' # improves error handling
  gem 'binding_of_caller' # used by better errors

  # Testing frameworks
  gem 'rspec-rails' # testing framework
  gem 'factory_girl_rails' # use factories, not fixtures
  gem 'capybara' # simulate browser activity
  gem 'fakeweb'

  # Automated testing
  gem 'guard' # automated execution of test suite upon change
  gem "guard-rspec" # guard integration with rspec

  # Only install the rb-fsevent gem if on Max OSX
  gem 'rb-fsevent' # used for Growl notifications
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

group :production do 
  gem 'rails_12factor'
  gem 'pg'
end
