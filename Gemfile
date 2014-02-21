source 'https://rubygems.org'

gem 'rails'
gem 'mysql2'

group :assets do
  gem 'compass-rails'
  # gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', platforms: :ruby
  gem 'angularjs-rails'
end

# doesn't work if put it to the assets group
gem 'less-rails'
gem 'twitter-bootstrap-rails'
gem 'turbolinks'
gem 'haml'
gem 'jquery-rails'

group :development do
  gem 'unicorn'
  gem 'capistrano'
end

group :development, :test do
  gem 'debugger'
  gem 'sextant'
  gem 'irbtools'
end

group :production do

end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end



