source 'https://rubygems.org'

gem 'rails', '4.2.2'
gem 'bcrypt',         '3.1.7'
gem 'faker', '1.4.2'
gem 'will_paginate',           '3.0.7'
gem 'bootstrap-will_paginate', '0.0.10'
gem 'bootstrap-sass', '3.2.0.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
# gem 'therubyracer', platforms: :ruby

gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do     
  gem 'sqlite3'    
  gem 'byebug'
    gem 'web-console', '~> 2.0.0.beta3'
  gem 'spring'
end

group :test do
    gem 'guard' # NOTE: this is necessary in newer versions
    gem 'minitest-reporters'
    gem 'mini_backtrace'
    gem 'guard-minitest'
end

group :production do
    gem 'pg'
    gem 'rails_12factor'
    gem 'puma', '2.11.1'
end


