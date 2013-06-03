source 'https://rubygems.org'
source 'http://gemcutter.org'

gem 'rails'
gem 'rack'
gem 'unicorn'

# database
gem 'pg'
gem 'hiredis'
gem 'redis-activesupport', :require => ["redis", "redis/connection/hiredis", "redis-activesupport"]
gem 'sinatra' # required by sidekiq/web
gem 'sidekiq'

# front end
gem 'slim'
gem 'jquery-rails-cdn'
gem 'jquery-rails'
gem 'underscore-rails'
gem 'twitter-bootstrap-markup-rails', '0.3.2.2'
gem 'formatize'
gem 'compass-rails'
gem 'sass-rails'
gem 'coffee-rails', '~> 3.2.1'
gem 'swfobject-rails'
gem 'js-routes'
# twitter bootstrap
gem "therubyracer"
gem "less-rails" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem 'twitter-bootstrap-rails', :git => 'https://github.com/seyhunak/twitter-bootstrap-rails.git'

gem 'devise'

# utilities
gem 'simple_form'
gem 'money'
gem 'money-rails'
gem 'countries'
gem 'htmlentities'
gem 'enumerize', :git => 'https://github.com/brainspec/enumerize.git', :ref => '9dc06ba60d0f134db726c2da52c8d255dbc07eba'
gem 'activemerchant', :require => 'active_merchant'
gem 'phonie'
gem 'encryptor'
gem 'acts_as_list'
gem 'rc_rails', :git => 'https://github.com/paolodona/resources_controller.git', :branch => 'master'
gem 'activerecord-import'
gem 'chronic_duration'
gem 'request_store' # Used instead of Thread.current, protects access in multithreaded environments
gem 'virtus' # used for form objects
gem 'paranoia' # sets records as deleted
gem "recurrence"

# paperclip with S3
gem 'paperclip'
gem 'aws-sdk'
gem 'remotipart'
gem 'lazy_high_charts'

# Email/SMS
gem 'sendgrid'
gem 'valid_email'
gem 'nexmo'
gem 'nokogiri' # required by premailer - but not listed as dependency
gem 'premailer', :git => 'https://github.com/lucaspiller/premailer.git'
gem 'premailer-rails'

# system health
gem 'airbrake' #, '3.0.9' # 3.1+ doesn't work with errbit currently
gem 'airbrake_user_attributes'
gem 'newrelic_rpm'

# pagination
gem 'kaminari', :git => 'https://github.com/amatsuda/kaminari.git'

# PDF/Excel generation
gem 'pdfkit'
gem 'spreadsheet_on_rails', :git => 'https://github.com/10to1/spreadsheet_on_rails.git'

# I18n
gem 'localeapp'
gem 'rails_locale_detection', :git => 'https://github.com/paolodona/rails_locale_detection.git', :branch => 'master'
# gem 'http_accept_language'

# Decorators
gem 'draper'
gem 'decorates_before_rendering'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'capistrano'
  gem 'capistrano-ext'
  gem 'capistrano-detect-migrations'
  gem 'capistrano-deploytags'
  gem 'bullet'
  gem 'sextant'
  gem 'annotate', :git => 'https://github.com/ctran/annotate_models.git'
  gem 'quiet_assets'
  # gem 'debugger'
  gem 'better_errors'
  gem 'binding_of_caller'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'rake'
  gem 'rspec-instafail'
  gem 'wkhtmltopdf-binary'
end

group :test do
  gem 'shoulda-matchers'
  gem 'json_spec'
  gem 'factory_girl'
  gem 'capybara'
  gem 'capybara-webkit', git: 'git://github.com/thoughtbot/capybara-webkit.git'
  gem 'capybara-screenshot' # Good to spot label and other changes
  gem 'fakeweb'
  gem 'fakeweb-matcher'
  gem 'timecop'
  gem 'launchy' #to open pages in integration tests
  gem 'database_cleaner'
  gem 'faker'
  gem 'test_after_commit'
  gem 'rspec-rerun'
  gem 'no_peeping_toms'
end
