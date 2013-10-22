source 'https://rubygems.org'
source 'http://gemcutter.org'

gem 'rails', '4.0.0'
gem 'rack'
gem 'unicorn'

# database
gem 'pg'
gem 'redis-activesupport', :git => 'https://github.com/jodosha/redis-store.git', :branch => 'master'
gem 'sinatra' # required by sidekiq/web
gem 'sidekiq'

# front end
gem 'slim'
gem 'jquery-rails-cdn'
gem 'jquery-rails'
gem 'underscore-rails'
gem 'twitter-bootstrap-markup-rails', :git => 'https://github.com/pusewicz/twitter-bootstrap-markup-rails.git', :branch => 'master'
gem "compass-rails", "~> 2.0.alpha.0"
gem 'sass-rails', :git => 'https://github.com/rails/sass-rails.git', :branch => 'master'
gem 'coffee-rails'
gem 'swfobject-rails', :git => 'https://github.com/geraudmathe/swfobject-rails.git', :branch => 'master'
gem 'js-routes'

# custom json views
gem 'rabl'
gem 'oj'

# twitter bootstrap
gem "therubyracer"
gem "less-rails" #Sprockets (what Rails 3.1 uses for its asset pipeline) supports LESS
gem 'twitter-bootstrap-rails', :git => 'https://github.com/seyhunak/twitter-bootstrap-rails.git'

gem "select2-rails"
gem 'devise'

# utilities
gem 'simple_form', :git => 'git://github.com/plataformatec/simple_form.git'
gem 'money'
gem 'money-rails', :git => 'https://github.com/RubyMoney/money-rails.git', :branch => 'master'
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
gem 'virtus', :git => 'https://github.com/solnic/virtus.git' # used for form objects
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
gem 'premailer', :github => 'lucaspiller/premailer'
gem 'premailer-rails'

# system health
gem 'airbrake' #, '3.0.9' # 3.1+ doesn't work with errbit currently
gem 'newrelic_rpm'

# pagination
gem 'kaminari', :git => 'https://github.com/amatsuda/kaminari.git'

# PDF/Excel generation
gem 'pdfkit'
gem 'spreadsheet_on_rails', :git => 'https://github.com/10to1/spreadsheet_on_rails.git'

# I18n
gem 'localeapp'
gem 'rails_locale_detection', :git => 'https://github.com/paolodona/rails_locale_detection.git', :branch => 'master'

# Decorators
gem 'draper'
gem 'decorates_before_rendering'
gem 'uglifier', '>= 2.1.2'

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
  # gem 'rails-footnotes', '>= 3.7.9'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'rake'
  gem 'rspec-instafail'
  gem 'wkhtmltopdf-binary'
end

group :test do
  gem 'shoulda-matchers'
  gem 'factory_girl'
  gem 'capybara'
  gem 'poltergeist'
  gem 'capybara-screenshot' # Good to spot label and other changes
  gem 'fakeweb'
  gem 'fakeweb-matcher'
  gem 'timecop'
  gem 'launchy' #to open pages in integration tests
  gem 'database_cleaner'
  gem 'faker'
  gem 'test_after_commit'
end
