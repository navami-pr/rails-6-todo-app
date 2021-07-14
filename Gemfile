source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.4'
# Use postgresql as the database for Active Record
gem 'pg', '~> 1.1'
# Use Puma as the app server
gem 'puma', '~> 5.0'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 5.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 4.1.0'
  # Display performance information such as SQL time and flame graphs for each request in your browser.
  # Can be configured to work on production as well see: https://github.com/MiniProfiler/rack-mini-profiler/blob/master/README.md
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem "rspec-rails"
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
  gem "rspec-rails"
end

group :test, :development do
  gem 'capybara',                  '~> 3.34'
  gem 'cucumber',                  '~> 3.0', require: false
  gem 'cucumber-rails',            '~> 1.6', require: false
  gem 'cucumber_characteristics',  '~> 0.0.6', require: false
  gem 'database_cleaner',          '~> 1.7'
  # # gem 'email_spec',                '~> 2.2'
  # # gem 'factory_bot_rails',         '~> 4.11'
  # # gem 'pry-byebug',                '~> 3.6'
  # # gem 'pry-doc',                   '~> 1.0'
  # # gem 'puma',                      '~> 5.0.4'
  # # gem 'rack-test',                 '~> 0.6'
  # # gem 'rspec-activemodel-mocks',   '~> 1.1'
  # # gem 'rspec-collection_matchers', '~> 1.1'
  # # gem 'rspec-its',                 '~> 1.3'
  # # gem 'rspec-mocks',               '~> 3.9'
  # # gem 'rspec-rails',               '~> 4.0'
  # gem 'selenium-webdriver',        '~> 3.14'
  # gem 'shoulda-matchers',          '~> 2.8''
end  

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

