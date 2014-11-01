source 'http://rubygems.org'

gem 'rails', '4.1.7'
gem 'rack'
gem 'unicorn'

# database
gem 'pg'

gem 'hiredis'
gem 'redis-activesupport', :require => ["redis", "redis/connection/hiredis", "redis-activesupport"]

gem 'sinatra' # required by sidekiq/web
gem 'sidekiq'
gem 'sidetiq', :git => 'https://github.com/tobiassvn/sidetiq' # cron jobs in sidekiq

# front end
gem "select2-rails"
gem "therubyracer"
gem 'coffee-rails'
gem 'jquery-rails'
gem 'jquery-rails-cdn'
gem 'js-routes'
gem 'sass-rails', "~>4.0.2"
gem 'slim'
gem 'swfobject-rails', :git => 'https://github.com/geraudmathe/swfobject-rails.git', :branch => 'master'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'underscore-rails'
gem 'foundation-rails', '5.2.2.0'
gem 'meta-tags', require:'meta_tags' # see https://github.com/kpumuk/meta-tags
gem 'redcarpet'
gem 'font-awesome-sass'

# custom json views
gem 'rabl'
gem 'oj'

gem 'devise'
gem 'devise_invitable', :git => 'http://github.com/scambra/devise_invitable', :ref => 'd3441d0f1083e9a858070aae64d1e683a2be42d2'

# utilities
gem 'simple_form', :git => 'http://github.com/plataformatec/simple_form.git'
gem 'money', '6.1.1', :git => 'http://github.com/RubyMoney/money.git'
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
gem 'aws-sdk'
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
gem 'airbrake'
gem 'newrelic_rpm'

# pagination
gem 'kaminari', :git => 'http://github.com/amatsuda/kaminari.git'

# PDF/CSV generation
gem 'pdfkit'
gem 'wkhtmltopdf-binary'

# I18n
gem 'localeapp'
gem 'rails_locale_detection', :git => 'http://github.com/paolodona/rails_locale_detection.git', :branch => 'master'
gem 'unlocalize', :git => 'http://github.com/paolodona/unlocalize', :branch => 'master'

# Decorators
gem 'draper', '~> 1.3'
gem 'decorates_before_rendering'
gem 'uglifier', '>= 2.1.2'

# sitemap
gem 'sitemap_generator'

gem 'utf8-cleaner' # leave this last so that middleware is the first in the chain

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
  gem "spring"
end

group :development, :test do
  gem 'rake'
  gem 'byebug'
  gem 'spring-commands-rspec'
  gem 'rspec', '~> 2.14.1'
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
  gem 'faker'
  gem 'selenium-webdriver'
end
