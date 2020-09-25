source 'https://rubygems.org'

plugin 'bundler-inject', '~> 1.1'
require File.join(Bundler::Plugin.index.load_paths('bundler-inject')[0], 'bundler-inject') rescue nil

gem 'cloudwatchlogger',    '~> 0.2.1'
gem 'manageiq-loggers',    '~> 0.5.0'
gem 'manageiq-messaging',  '~> 0.1.2'
gem 'optimist',            '~> 3.0'
gem 'prometheus_exporter', '~> 0.4.5'

gem 'sources-api-client', '~> 3.0'
gem 'topological_inventory-core', '~> 1.1.7'

group :development, :test do
  gem 'rspec-rails',         '~>3.8'
  gem 'rubocop',             '~>0.69.0', :require => false
  gem 'rubocop-performance', '~>1.3',    :require => false
  gem 'simplecov',           '~>0.17.1'
end
