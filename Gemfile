source 'https://rubygems.org'
gemspec

if !ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri if RUBY_VERSION >= '2.2.0'
  gem 'yard',   require: false
end

gem 'hanami-utils', '~> 0.7', require: false, github: 'hanami/utils', branch: '0.7.x'
gem 'haml'

gem 'simplecov', require: false
gem 'coveralls', require: false
