# this gemfile is only required for running the features/tests

source :rubygems

gem 'rails', '3.0.0.rc'

git 'git@github.com:svenfuchs/adva-cms2.git' do
  gem 'adva-core'
  gem 'adva-blog'
  gem 'adva-cart'
  gem 'adva-catalog'
  gem 'adva-contacts'
  gem 'adva-static'
  gem 'adva-user'
end

group :development do
  gem 'tidy_ffi'
end

group :test do
  gem 'sqlite3-ruby', '1.2.5'
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'webrat', '0.7.0'
  gem 'thor'
  gem 'ruby-debug'
  gem 'mocha'
  gem 'fakefs', :require => 'fakefs/safe'
  gem 'test_declarative'
  gem 'database_cleaner'
end
