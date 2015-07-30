source 'https://rubygems.org'
source 'https://rails-assets.org' # required to download raisl-assets-underscore

# Additional gemfiles for Heroku
ruby '2.2.2'
gem 'rails_12factor', group: :production
gem 'puma',           group: :production

gem 'devise'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use sqlite3 as the database for Active Record
gem 'pg', group: [:production, :test]
gem 'sqlite3', group: :development
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
# gem 'turbolinks'
# COMMENTED OUT FOR THE PURPOSE OF MAKING GEOCODE WORK PROPERLY
# ADD THE FOLLOWING LINE TO application.js IF YOU WANT TO HAVE TURBOLINKS WORKS AGAIN
# //= require turbolinks
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Usual front-end gems
gem 'bootstrap-sass'
gem 'font-awesome-sass'
gem 'simple_form'



# Image Magick and PaperClip
gem 'aws-sdk', '< 2.0'
gem 'paperclip'

# Geolocation stuffs
gem 'geocoder'
gem 'gmaps4rails'
gem 'rails-assets-underscore'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'

    # better errors
  gem "better_errors"
  gem "binding_of_caller"
  # seeder
  gem "faker"
end
