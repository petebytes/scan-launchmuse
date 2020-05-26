source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.6'

# Default Gems
gem 'rails', '~> 6.0.2' # Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'pg', '>= 0.18', '< 2.0' # Use postgresql as the database for Active Record
gem 'puma', '~> 4.3.0' # Use Puma as the app server
# But sass-rails 5 generates deprecation warnings. It is wrapper over sassc-rails, so change dependency to gem 'sassc-rails', '~> 2.0'
gem 'sassc-rails', '~> 2.0'
gem 'webpacker', '~> 4.0'
gem 'turbolinks', '~> 5' # Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'jbuilder', '~> 2.9'
gem 'bootsnap', '>= 1.4.5', require: false # Reduces boot times through caching; required in config/boot.rb
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby] # Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'sprockets', '~> 3.7.2' # Added here manually to manage the version v4 is available but has breaking changes

# Added Gems
gem 'ahoy_matey'
gem 'airbrake', '~> 9.5.0'
gem 'aws-sdk-s3', require: false
gem "chartkick"
gem 'blazer'
gem 'delayed_job_active_record'
gem 'devise'
gem 'devise-two-factor'
gem 'devise_invitable', '~> 2.0.1'
gem 'groupdate'
gem 'image_processing', '~> 1.10', '>= 1.10.3'
gem 'money-rails'
gem 'omniauth-facebook', '~> 5.0.0'
gem 'omniauth-twitter', '~> 1.4.0'
gem 'omniauth-google-oauth2', '~> 0.8.0'
gem 'omniauth-github', '~> 1.3'
gem 'omniauth-amazon', '~> 1.0', '>= 1.0.1'
gem 'rqrcode'
gem 'redis', '~> 4.0' # Use Redis adapter to run Action Cable in production
gem 'mini_magick', '~> 4.9', '>= 4.9.5'
gem 'name_of_person'
gem 'rack-cors'
gem 'sendgrid-ruby'
gem 'split', require: 'split/dashboard' # A/B or Split testing
gem 'stripe', '~> 5.11'
gem 'stripe_event', '~> 2.3' # Handles Stripe webhook endpoints
gem 'twitter'
gem 'shrine', "~> 3.2"
gem "uppy-s3_multipart", ">= 0.3.2"
gem 'marcel' # Find the mime type of files, examining file, filename and declared type
gem 'fastimage' # finds the size or type of an image given its uri
gem 'pretender'
gem 'whenever', require: false
gem 'maxminddb' # Geocoding for Ahoy
gem 'friendly_id', '~> 5.3'
gem 'streamio-ffmpeg', '~> 3.0', '>= 3.0.2' # for video transcoding and screenshot
gem 'ruby-vips', '~> 2.0', '>= 2.0.7'
gem 'sitemap_generator'
gem 'mautic', '~> 2.3'

group :development, :test do
  gem 'dotenv-rails', '~> 2.7.2'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw] # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'rspec-rails', '~> 4.0.0.beta3' # TODO update rspec-rails gem
  gem 'factory_bot_rails'
  gem 'rb-fsevent', require: false
  gem 'faker'
  gem 'foreman'
  gem 'overcommit', require: false
end

group :development do
  gem 'listen', '~> 3.2.1'
  gem 'web-console', '>= 4.0.0' # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'spring' # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'annotate' # Annotate Rails classes with schema and optionally routes info
  gem 'rubocop'
  gem 'rubocop-rspec'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'brakeman' # A static analysis security vulnerability scanner for Ruby on Rails applications https://brakemanscanner.org/
  gem 'bundler-audit' # Patch-level verification for Bundler
  gem 'reek', require: false
  gem 'rails_best_practices', require: false
end

group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  # gem 'webdrivers' # not needed if running test remotely (selenium grid)
  gem 'shoulda-matchers'
  gem 'rails-controller-testing'
  gem 'simplecov', require: false
  gem 'vcr' # record http requests
  gem 'webmock' # intercept http requests
  gem 'email_spec'
  gem 'rspec-retry' # Unlike rspec, this doesn't need to be included in development group
end
