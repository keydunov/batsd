source "https://rubygems.org"

gem 'eventmachine', '~>1.0.0.rc.4'
gem 'redis', "~> 3.1.0"
if RUBY_PLATFORM == 'java'
  gem 'json-jruby'
else
  gem 'json'
end

group :development, :test do
  gem 'yard'
  gem 'mocha'
  gem 'rake'
end
