source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '7.0.8.1'
gem 'json', '~> 1.7.7'

group :development do
  gem 'sqlite3'
  gem 'pry-rails'
end

group :production do
  gem 'thin', '>= 1.6.2'
  gem 'pg'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', '~> 5.0.8'
  gem 'coffee-rails', '~> 4.2.2'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'rspec-rails', '~> 2.14', '>= 2.14.1'
  gem 'shoulda'
end

# jQuery
gem 'jquery-rails', '>= 4.0.1'
gem 'jquery-ui-rails', '>= 4.1.1'

# Kickstarter's awesome Amazon Flexible Payments gem
gem 'amazon_flex_pay'

# Configuration File
gem 'rails_config'

# For Heroku
gem 'rails_12factor'
