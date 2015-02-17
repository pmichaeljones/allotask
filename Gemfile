source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.2.0'
gem 'pg'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'faker'
gem 'fabrication'
gem 'haml-rails'
gem 'cancan'
gem 'newrelic_rpm'
gem 'devise'
gem 'high_voltage', '~> 2.2.1'
gem 'recipient_interceptor'
gem 'figaro'

# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use Unicorn as the app server
gem 'unicorn'

group :development do
  gem 'thin'
  gem "better_errors"
  gem "binding_of_caller"
end

group :test do
  gem 'launchy'
  gem 'capybara'
  gem 'shoulda'
  gem 'shoulda-matchers', require: false
  gem 'database_cleaner', '1.2.0'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :production do
  gem 'rails_12factor'
end

