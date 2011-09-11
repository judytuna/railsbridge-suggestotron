source 'http://rubygems.org'

gem 'rails', '3.1.0'
gem 'sqlite3'
gem 'jquery-rails'
gem 'rake'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
end

group :test, :development do
  gem 'rspec-rails', '>= 2.3.0'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'cucumber-rails'
  gem 'launchy'
  #json is only for judy's computer
  gem 'json' 
end

group :production do
  # fix for putting rails 3.1 on heroku
  gem 'therubyracer-heroku', '0.8.1.pre3'
  gem 'pg'
end
