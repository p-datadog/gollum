source 'https://rubygems.org'

gem 'warbler', git: 'https://github.com/jruby/warbler' if RUBY_PLATFORM == 'java'

group :test do
  gem 'selenium-webdriver', require: false
  gem 'capybara', require: false
end

group :development do
  gem 'google-protobuf', force_ruby_platform: RUBY_PLATFORM.include?('linux-musl')
  gem 'sassc-embedded', '~> 1.80'
end

gemspec

gem 'rake', '~> 13.0'
