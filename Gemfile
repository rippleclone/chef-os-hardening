# encoding: utf-8

source 'https://rubygems.org'

gem 'berkshelf',  '~> 4.0'
gem 'chef',       '>= 12.0'
gem 'inspec', '~> 0.9'

group :test do
  gem 'rake'
  gem 'chefspec',   '~> 4.2.0'
  gem 'foodcritic', '~> 4.0'
  gem 'thor-foodcritic'
  gem 'rubocop',    '~> 0.28.0'
  gem 'coveralls',  require: false
  gem 'bundler', '~> 1.5'
  gem 'minitest', '~> 5.5'
  gem 'simplecov', '~> 0.10'
end

group :development do
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-kitchen'
  gem 'guard-rubocop'
  gem 'guard-foodcritic'
end

group :integration do
  gem 'test-kitchen', '~> 1.0'
  gem 'kitchen-vagrant'
  gem 'kitchen-sharedtests', '~> 0.2.0'
  gem 'kitchen-inspec', '~> 0.9'
  gem 'concurrent-ruby', '~> 0.9'
end

group :openstack do
  gem 'kitchen-openstack'
end
