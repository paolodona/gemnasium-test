source 'https://rubygems.org'
source 'http://gemcutter.org'

gem 'rails'
gem 'rack'

gem 'unicorn'

gem 'jquery-rails-cdn'
gem 'jquery-rails'
gem 'underscore-rails'
gem 'pg'

gem 'twitter-bootstrap-markup-rails', :git => 'https://github.com/marcocampana/twitter-bootstrap-markup-rails.git', :branch => 'master'
gem 'devise'

gem 'money'
gem 'money-rails'

gem 'countries'
gem 'htmlentities'
gem 'enumerize', :git => 'https://github.com/brainspec/enumerize.git', :ref => '9dc06ba60d0f134db726c2da52c8d255dbc07eba'

# paperclip with S3
gem 'paperclip'
gem 'aws-sdk'
gem 'remotipart'
gem 'lazy_high_charts'

# Email
gem 'sendgrid'
gem 'valid_email'

gem 'activemerchant', :require => 'active_merchant'

gem 'airbrake' #, '3.0.9' # 3.1+ doesn't work with errbit currently
gem 'airbrake_user_attributes'
gem 'newrelic_rpm'

# pagination
gem 'kaminari', :git => 'https://github.com/amatsuda/kaminari.git'

gem 'nexmo'

gem 'hiredis'
gem 'redis-activesupport', :require => ["redis", "redis/connection/hiredis", "redis-activesupport"]

gem 'slim'
gem 'sinatra' # required by sidekiq/web
gem 'sidekiq'

gem 'phonie'

gem 'formatize'

gem 'nokogiri' # required by premailer - but not listed as dependency
gem 'premailer', :git => 'https://github.com/lucaspiller/premailer.git'
gem 'premailer-rails'

gem 'pdfkit'

gem 'encryptor'

gem 'spreadsheet_on_rails', :git => 'https://github.com/10to1/spreadsheet_on_rails.git'

gem 'acts_as_list'
gem 'rc_rails'

gem 'coffee-rails', '~> 3.2.1'
gem 'activerecord-import'

gem 'simple-navigation'

gem 'compass-rails'
gem 'sass-rails'

gem 'chronic_duration'
gem 'localeapp'
gem 'http_accept_language'

gem 'draper'
gem 'decorates_before_rendering'

gem 'swfobject-rails'
gem 'js-routes'
gem 'request_store' # Used instead of Thread.current, protects access in multithreaded environments

gem 'virtus' # used for form objects

# twitter bootstrap
gem "therubyracer"
gem "less-rails" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem 'twitter-bootstrap-rails', :git => 'git://github.com/seyhunak/twitter-bootstrap-rails.git'

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
  gem 'debugger'
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
  gem 'capybara-webkit'
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
