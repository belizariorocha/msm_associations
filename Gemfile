source 'http://rubygems.org'

gem "starter_generators", :git => "https://github.com/raghubetina/starter_generators"

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '5.0.2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'sqlite3'

group :development, :test do
  gem "dotenv-rails"
  gem "factory_girl_rails"
  gem "rspec-rails"
  gem "pry-rails"
end

group :development do
  gem "awesome_print"
  gem "better_errors"
  gem "binding_of_caller"
  gem "letter_opener"
  gem "listen"
  gem "wdm" if Gem.win_platform?
end

group :test do
  gem "capybara"
  # gem "database_cleaner"
  gem "shoulda-matchers"
  gem "webmock"
end

group :development, :test do
  gem 'dotenv-rails'
  gem 'pry-rails'
  gem 'grade_runner', github: 'firstdraft/grade_runner'
  gem 'web_git', github: 'firstdraft/web_git'
end

group :development do
  gem 'annotate'
  gem 'awesome_print'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'firstdraft_generators', github: 'firstdraft/firstdraft_generators'
  gem 'letter_opener'
  gem 'meta_request'
  gem 'wdm', platforms: [:mingw, :mswin, :x64_mingw]
end

group :test do
  gem 'capybara'
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'webmock'
end

gem 'bootstrap-sass'
gem 'font-awesome-sass', '~> 4.7.0'
