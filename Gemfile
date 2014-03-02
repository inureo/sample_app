source 'https://rubygems.org'

# Set ruby version
ruby '2.1.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.0.rc1'
# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3', groups: %w(test development), require: false
  gem 'rspec-rails', groups: %w(test development), require: false
end

group :test do
  gem 'selenium-webdriver', groups: %w(test), require: false
  gem 'capybara', groups: %w(test), require: false
end

gem 'sass-rails', '4.0.1'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'

group :doc do
  gem 'sdoc', '~> 0.4.0', groups: %w(doc), require: false
end

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

group :production do
  gem 'pg', '0.15.1', groups: %w(production), require: false
  gem 'rails_12factor', '0.0.2'
end
