source 'http://rubygems.org'

gem 'rails', '4.1.14'
gem 'rack'
gem 'unicorn'

# database
gem 'pg'

gem 'hiredis'
gem 'redis-activesupport', :require => ["redis", "redis/connection/hiredis", "redis-activesupport"]

gem 'sinatra' # required by sidekiq/web
gem 'sidekiq', "~>3.3.0"
gem 'sidetiq', :git => 'https://github.com/tobiassvn/sidetiq', :branch => 'master' # cron jobs in sidekiq
gem 'sidekiq-throttler'

gem 'stripe'

# front end
gem "select2-rails"
gem "therubyracer"
gem 'coffee-rails'
gem 'js-routes'
gem 'sass-rails'
gem 'slim'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'underscore-rails'
gem 'foundation-rails', '5.5.1.2'
gem 'redcarpet'
gem 'font-awesome-sass'
source 'https://rails-assets.org' do
  gem 'rails-assets-jquery'
  gem 'rails-assets-jquery-ujs'
  gem 'rails-assets-sweetalert'
  gem 'rails-assets-intl-tel-input'
end

# custom json views
gem 'rabl'
gem 'oj'

gem 'devise'
gem 'devise_invitable', :git => 'http://github.com/scambra/devise_invitable', :ref => 'd3441d0f1083e9a858070aae64d1e683a2be42d2'

# utilities
gem 'simple_form', :git => 'http://github.com/plataformatec/simple_form.git'
gem 'money', '6.4.0'
gem 'money-rails'
gem 'countries', :git => 'http://github.com/hexorx/countries', :branch => 'master'
gem 'phony'
gem 'htmlentities'
gem 'enumerize', :git => 'http://github.com/brainspec/enumerize.git', :ref => '9dc06ba60d0f134db726c2da52c8d255dbc07eba'
gem 'encryptor'
gem 'acts_as_list'
gem 'rc_rails', :git => 'http://github.com/paolodona/resources_controller.git', :branch => 'master'
gem 'activerecord-import'
gem 'chronic_duration'
gem 'request_store', '~> 1.0.3' # Used instead of Thread.current, protects access in multithreaded environments
gem 'virtus', :git => 'http://github.com/solnic/virtus.git' # used for form objects
gem 'paranoia' # sets records as deleted
gem "recurrence" # for scheduling visits
gem "liquid"     # to parse address templates in country objects
gem "date_validator"
gem "browser"
gem 'wicked' # Wizards

# uploads
gem 'carrierwave'
gem 'fog'
gem 'aws-sdk', '~> 1.57'
gem 'remotipart'
gem 'mini_magick'
# gem 'lazy_high_charts'

# Email/SMS
gem 'sendgrid'
gem 'valid_email'
gem 'nexmo'
gem 'ringcaptcha', :git => 'https://github.com/paolodona/ringcaptcha.git'
gem 'nokogiri' # required by premailer - but not listed as dependency
gem 'premailer'
gem 'premailer-rails'

# system health
gem 'airbrake', '~> 5.0.0'
gem 'newrelic_rpm'

# pagination
gem 'kaminari', :git => 'http://github.com/amatsuda/kaminari.git'

# PDF/CSV generation
gem 'pdfkit'
gem 'wkhtmltopdf-binary'
gem 'render_anywhere', :require => false
gem 'uglifier', '>= 2.1.2'

# Geolocation
gem 'geocoder'

gem 'utf8-cleaner' # leave this last so that middleware is the first in the chain

group :development do
  gem 'capistrano', '~> 3.4.0'
  gem 'capistrano-rails', '~> 1.1'
  gem 'capistrano-faster-assets', '~> 1.0'
  gem 'capistrano-bundler', '~> 1.1.2'
  gem 'capistrano-rbenv', '~> 2.0'
  gem 'capistrano-deploytags', '~> 1.0.0', require: false
  gem "airbrussh", :require => false
  gem 'bullet'
  gem 'sextant'
  gem 'annotate', :git => 'http://github.com/ctran/annotate_models.git'
  gem 'quiet_assets'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem "spring"
  gem 'iye', :git => 'https://github.com/paolodona/iye.git', :branch => 'master'
end

group :development, :test do
  gem 'rake'
  gem 'byebug'
  gem 'spring-commands-rspec'
  gem 'rspec', '~> 2.14.1'
  gem 'faker'
  gem 'awesome_print'
  gem 'puma' # to test webhooks with ngrok
end

group :test do
  gem 'rspec-rails'
  gem 'shoulda-matchers'
  gem 'factory_girl'
  gem 'capybara'
  gem 'capybara-screenshot'
  gem 'fakeweb'
  gem 'timecop'
  gem 'launchy' #to open pages in integration tests
  gem 'selenium-webdriver', '>=2.48.0'
end
