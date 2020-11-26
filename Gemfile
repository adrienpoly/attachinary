source 'http://rubygems.org'

# Declare your gem's dependencies in attachinary.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Current stable version, actual version will be selected in CI by appraisal
gem 'rails', '~> 5.1.0'

# used by the dummy application
gem 'jquery-rails'
gem 'cloudinary'
gem 'simple_form'

# Assets gems used in dummy application
gem 'coffee-rails'
gem 'sass-rails'
gem 'bootstrap-sass', '~> 3.3.5'

source 'https://rails-assets.org' do
  gem 'rails-assets-blueimp-file-upload', '7.2.1'
end

# Stick with a working configuration
gem 'mongoid'

group :development, :test do
  gem 'appraisal'
  gem 'pry'
  gem 'sqlite3'
  gem 'rspec-rails', '~> 3.5'
  gem 'valid_attribute'
  gem 'capybara', '>= 2.15.2'
  gem 'capybara-screenshot'
  gem 'selenium-webdriver'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'vcr'
  gem 'webmock'
  gem 'travis'
end


# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

# To use debugger
# gem 'debugger'
