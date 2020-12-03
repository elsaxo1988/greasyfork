source 'https://rubygems.org'

ruby '2.6.6'

gem 'bootsnap'
gem 'daemons'
gem 'devise'
gem 'devise-i18n', git: 'https://github.com/tigrish/devise-i18n.git'
gem 'diffy'
gem 'mini_racer'
gem 'mysql2'
gem 'newrelic_rpm'
gem 'public_suffix'
gem 'rack-attack'
gem 'rails', git: 'https://github.com/rails/rails.git', branch: '6-1-stable'
gem 'rails-i18n'
gem 'redcarpet'
gem 'sanitize'
gem 'sidekiq'
gem 'strip_attributes'
gem 'thinking-sphinx', git: 'https://github.com/pat/thinking-sphinx', branch: 'develop'
gem 'transifex-ruby', git: 'https://github.com/tmaesaka/transifex-ruby.git'
gem 'ts-sidekiq-delta'
gem 'user_agent_parser'
gem 'webpacker', '~> 5.x'
gem 'will_paginate'
gem 'will-paginate-i18n'

gem 'hiredis'
gem 'redis'

gem 'akismet'
gem 'detect_language'
gem 'email_address'
gem 'it'
gem 'memoist'
gem 'omniauth', '>= 1.6.0'
gem 'omniauth-github'
gem 'omniauth-gitlab'
gem 'omniauth-google-oauth2', '>= 0.4.1'
gem 'omniauth-rails_csrf_protection'

gem 'active_storage_validations'
gem 'aws-sdk-s3', require: false
gem 'image_processing'

gem 'rails-observers'
gem 'rb-readline'
gem 'recaptcha', require: 'recaptcha/rails'
# Rails gets support in https://github.com/rails/rails/pull/28297
gem 'rails_same_site_cookie'

gem 'byebug', group: [:development, :test]

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'capistrano', '~> 3.7'
  gem 'capistrano-bundler'
  gem 'capistrano-passenger'
  gem 'capistrano-rails'
  gem 'capistrano-rbenv'
  # capistrano-sidekiq 1.0.3 is marked as incompatible with Sidekiq 6, but really it is compatible, as long as you use the systemd stuff.
  gem 'capistrano-sidekiq', git: 'https://github.com/rwojnarowski/capistrano-sidekiq.git', ref: '8a8a2edf86dfcdebd69dafc4f96adc55745aecde'
  gem 'listen'
  gem 'rubocop'
  gem 'rubocop-minitest', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', require: false
end

group :test do
  gem 'bundler-audit'
  gem 'capybara'
  gem 'minitest-around'
  gem 'mocha'
  gem 'selenium-webdriver'
  gem 'webdrivers', '~> 4.0'
end
