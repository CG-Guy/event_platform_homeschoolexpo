source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.2'
# Use mysql as the database for Active Record
gem 'pg'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
gem 'bcrypt', '~> 3.1.7'
gem 'pagy', '~> 3.5'
# Use Active Storage variant
#gem 'image_processing', '~> 1.2'

#Rails Settings Cached
gem "rails-settings-cached", "~> 2.0"
gem 'city-state'
gem "select2-rails"

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

gem "devise"
gem "hpricot"
gem "ruby_parser"
gem 'dotenv-rails'
gem "validate_url"
#
gem 'nested_form_fields'

gem "pundit"

gem 'image_processing'

gem 'mail'

gem "recaptcha", require: "recaptcha/rails"

gem 'zoom_rb'

gem 'acts-as-taggable-on', '~> 6.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  #gem 'rspec-rails', '~> 3.5'
  #gem 'factory_girl_rails'
  gem 'capybara', '>= 2.15'
  gem 'database_cleaner'

  %w[rspec-core rspec-expectations rspec-mocks rspec-rails rspec-support].each do |lib|
        gem lib, git: "https://github.com/rspec/#{lib}.git", branch: 'master' # Previously '4-0-dev' or '4-0-maintenance' branch
    end
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
