source "http://rubygems.org"

gem "rails"

gem "pg", :require => "pg"

gem "jquery-rails"
gem "devise", :git => "https://eefcd2aaafca2dbcae157bb2c73bebe256ac124e:x-oauth-basic@github.com/renderedtext/devise.git"
gem "omniauth-facebook"
gem "kaminari"
gem "carrierwave", :git => "https://eefcd2aaafca2dbcae157bb2c73bebe256ac124e:x-oauth-basic@github.com/renderedtext/carrierwave.git"
gem "meta_search", :git => "https://eefcd2aaafca2dbcae157bb2c73bebe256ac124e:x-oauth-basic@github.com/renderedtext/meta_search.git"
gem "dynamic_form"
gem "heroku"
gem "coffee-rails"
gem "less-rails"
gem "twitter-bootstrap-rails"

group :assets do
  gem "therubyracer", :platform => :ruby
end

group :test, :development do
  gem "rspec-rails"
  gem "spork-rails"
  gem "debugger"
  gem "awesome_print"
end

group :development do
  gem "chronic"
  gem "admin_view"
  gem "debugger"
end

group :test do
  gem "factory_girl_rails"
  gem "cucumber-rails", :require => false
  gem "database_cleaner"
  gem "selenium-webdriver"
  gem "capybara"
  gem "shoulda"
  gem "email_spec"
end

group :production, :development do
  gem "thin"
end
