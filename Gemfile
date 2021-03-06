source 'https://rubygems.org'

gem 'rails', '4.0.2'

gem 'pg' # Use postgres as the database for Active Record

gem 'sass-rails', '~> 4.0.0' # Use SCSS for stylesheets

gem 'uglifier', '>= 1.3.0' # Use Uglifier as compressor for JavaScript assets

# gem 'coffee-rails', '~> 4.0.0' # Use CoffeeScript for .js.coffee assets and views

gem 'jquery-rails' # Use jquery and Zepto as the JavaScript library

gem 'turbolinks' # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'jbuilder', '~> 1.2' # Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder

gem 'zurb-foundation' # Adds foundation

gem 'redcarpet'

gem "minitest-rails" # Adds mini-test framework

gem 'devise' # Adds Devise user authentication
gem 'omniauth' # Adds base omniauth
gem 'omniauth-twitter' # Adds twitter oauth login
gem 'figaro', '~> 0.7.0'
gem 'rakismet' # Adds Akismet integration

gem 'pundit' # Adds policy-based authorization support
gem 'coveralls', require: false # Coveralls gem for test coverage

gem 'carrierwave' # Handles file uploads
gem 'rmagick' # Imagemagick gem
gem 'fog' # Handles Amazon S3 uploads
gem 'sidekiq' # Handles background queue
gem 'whenever', :require => false # CRON JOBS
gem 'postmark-mitt' # Enables inbound emails from Postmark

group :test do

  gem 'minitest-rails-capybara'
  gem 'turn'
end

group :development do
  gem 'capistrano',  '~> 3.1'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-rvm'
  gem 'letter_opener' # Send emails in developer mode
end

group :doc do
  gem 'sdoc', require: false # bundle exec rake doc:rails generates the API under doc/api.
end

group :production do
  gem 'rails_12factor'
  gem 'unicorn'

  gem 'postmark-rails', '~> 0.7.0' # Sends email through postmark
end

ruby "2.0.0"
