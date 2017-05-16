source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.3'
gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
# Added gems
gem 'mysql2'
gem 'bootstrap-sass'
gem 'devise'

gem 'sprockets'
gem 'bcrypt-ruby'
gem 'jquery-turbolinks'
gem 'shoulda'
gem 'date_validator'
gem 'foreigner'
gem 'will_paginate'
gem 'will_paginate-bootstrap'
gem 'searchkick'
gem 'money'
gem 'money-rails'
gem 'elasticsearch-model'
gem 'elasticsearch-rails'
gem 'geocoder'
gem 'geo_ip'
gem 'stripe'
gem 'wkhtmltopdf-binary'
gem 'wicked_pdf'
gem 'premailer-rails'
gem 'nokogiri'
gem 'acts_as_votable'
gem 'aws-sdk'
gem 'carrierwave'
gem 'fog'
gem 'figaro'
gem 'mini_magick'
gem 'responders'
gem 'elastic-beanstalk'
gem 'font-awesome-rails' # Font-awesome icon
gem 'mail_form' #Forms, mail
gem 'simple_form' #Forms, mail


group :development,:test do
  gem 'rspec-rails'
  #gem 'rspec-its'
  gem 'simplecov', :require => false
  gem 'guard-rspec'
  #gem 'spork-rails'
  #gem 'guard-spork'
  gem 'childprocess'
  gem 'rails-erd'
  gem 'pry-rails'
  gem 'guard-rails'
  gem 'guard-livereload'
  gem 'guard-bundler'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'launchy'
end


group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

group :production do
  gem 'pg'
  gem 'rails_12factor', '~> 0.0.2'
end