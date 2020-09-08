source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem "rails", "~> 6.0.3", ">= 6.0.3.2"

gem "autoprefixer-rails", "~> 9.8", ">= 9.8.6.1"
gem "bootsnap", ">= 1.4.2", require: false
gem "devise", "~> 4.7", ">= 4.7.2"
gem "font-awesome-sass", "~> 5.13"
gem 'geocoder', '~> 1.6', '>= 1.6.3'
gem 'measured-rails', '~> 2.5', '>= 2.5.2'
gem "pg", ">= 0.18", "< 2.0"
gem "puma", "~> 4.1"
gem "pundit", "~> 2.1"
gem "redis", "~> 4.0"
gem "sass-rails", ">= 6"
gem "sidekiq", "~> 6.1", ">= 6.1.1"
gem "simple_form", "~> 5.0", ">= 5.0.2"
gem "turbolinks", "~> 5"
gem "turbolinks_render"
gem "webpacker", "~> 4.0"

group :development, :test do  gem 'pry-byebug'
  gem 'pry-rails'
  gem 'dotenv-rails'
  gem "pry-byebug"
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem "rubocop", "~> 0.77.0", require: false
  gem "rubocop-performance", "~> 1.5", ">= 1.5.1"
  gem "rubocop-rails", "~> 2.4"

  gem "listen", "~> 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "mocha"
  gem "selenium-webdriver"
  gem "simplecov", require: false
  gem "webdrivers"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
