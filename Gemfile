source 'http://rubygems.org'
ruby '2.0.0'

gem 'rails', '3.2.16'

platforms :ruby do
  gem 'unicorn'
end

gem 'pg' # postgres
gem 'json'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'figaro'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 3.2'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier',     '>= 1.0.3'
  gem 'compass-rails'
end

group :development, :test do
  gem "rspec-rails"
  gem 'rspec-cells'
  gem "factory_girl_rails"
  gem "cucumber-rails", :require => false
  gem 'pry-rails'
  gem 'awesome_print'
end

group :development do
  gem 'sextant'
  gem 'rails-footnotes'
  gem 'quiet_assets'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'thin'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'shoulda-matchers'
  gem 'launchy'
  gem 'forgery'
  gem 'poltergeist' # requires phantom-js. Headless running of cucumber/capybara tests.
  gem 'delorean'
  gem 'fuubar'
end