source 'http://rubygems.org'

gem 'rails', '4.0.3'
gem 'rack'
gem 'unicorn'

# database
gem 'pg'
gem 'redis-activesupport'
gem 'sinatra' # required by sidekiq/web
gem 'sidekiq'

# front end
gem "select2-rails"
gem "therubyracer"
gem 'bourbon'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'jquery-rails-cdn'
gem 'js-routes'
gem 'neat'
gem 'sass-rails', :git => 'https://github.com/rails/sass-rails.git', :branch => 'master'
gem 'slim'
gem 'swfobject-rails', :git => 'https://github.com/geraudmathe/swfobject-rails.git', :branch => 'master'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'underscore-rails'

# custom json views
gem 'rabl'
gem 'oj'

gem 'devise'
gem 'devise_invitable', :git => 'http://github.com/scambra/devise_invitable', :ref => 'd3441d0f1083e9a858070aae64d1e683a2be42d2'

# utilities
gem 'simple_form', :git => 'http://github.com/plataformatec/simple_form.git'
gem 'money', :git => 'http://github.com/RubyMoney/money.git', :tag => 'v6.1.0.beta1'
gem 'monetize'
gem 'money-rails', :git => 'http://github.com/RubyMoney/money-rails.git', :branch => 'upgrade_to_money_6_1'
gem 'countries', :git => 'http://github.com/hexorx/countries', :branch => 'master'
gem 'htmlentities'
gem 'enumerize', :git => 'http://github.com/brainspec/enumerize.git', :ref => '9dc06ba60d0f134db726c2da52c8d255dbc07eba'
gem 'activemerchant', :require => 'active_merchant'
gem 'encryptor'
gem 'acts_as_list'
gem 'rc_rails', :git => 'http://github.com/paolodona/resources_controller.git', :branch => 'master'
gem 'activerecord-import'
gem 'chronic_duration'
gem 'request_store' # Used instead of Thread.current, protects access in multithreaded environments
gem 'virtus', :git => 'http://github.com/solnic/virtus.git' # used for form objects
gem 'paranoia' # sets records as deleted
gem "recurrence" # for scheduling visits
gem "liquid"     # to parse address templates in country objects
gem "date_validator"

gem 'aws-sdk'
gem 'remotipart'
# gem 'lazy_high_charts'

# Email/SMS
gem 'sendgrid'
gem 'valid_email'
gem 'nexmo'
gem 'nokogiri' # required by premailer - but not listed as dependency
gem 'premailer' # We use the original gem to use the data-premailer attribute, :git => 'http://github.com/lucaspiller/premailer.git'
gem 'premailer-rails'
gem 'mail_view'

# system health
gem 'airbrake'
gem 'newrelic_rpm'

# pagination
gem 'kaminari', :git => 'http://github.com/amatsuda/kaminari.git'

# PDF/Excel generation
gem 'pdfkit'
gem 'spreadsheet_on_rails', :git => 'http://github.com/10to1/spreadsheet_on_rails.git'
gem 'wkhtmltopdf-binary'

# I18n
gem 'localeapp'
gem 'rails_locale_detection', :git => 'http://github.com/paolodona/rails_locale_detection.git', :branch => 'master'
gem 'unlocalize', :git => 'http://github.com/paolodona/unlocalize', :branch => 'master'

# Decorators
gem 'draper'
gem 'decorates_before_rendering'
gem 'uglifier', '>= 2.1.2'

group :development do
  gem 'capistrano', '~> 2.15'
  gem 'capistrano-ext', '~> 1.2'
  gem 'capistrano-detect-migrations', '~> 0.6'
  gem 'capistrano-deploytags', '~> 0.8'
  gem 'bullet'
  gem 'sextant'
  gem 'annotate', :git => 'http://github.com/ctran/annotate_models.git'
  gem 'quiet_assets'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'rake'
  gem 'rspec-instafail'
  gem 'byebug'
end

group :test do
  gem 'shoulda-matchers'
  gem 'factory_girl'
  gem 'capybara'
  gem 'poltergeist', :git => 'https://github.com/jonleighton/poltergeist.git', :branch => 'master'
  gem 'capybara-screenshot' # Good to spot label and other changes
  gem 'fakeweb'
  gem 'fakeweb-matcher'
  gem 'timecop'
  gem 'launchy' #to open pages in integration tests
  gem 'database_cleaner'
  gem 'faker'
  gem 'selenium-webdriver'
end
