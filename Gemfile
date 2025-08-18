
source 'https://rubygems.org'



# Ruby and Rails
ruby '3.3.5'
gem 'rails', '~> 7.1.0'
gem 'puma', '~> 6.0'
gem 'sqlite3', '~> 1.6'
gem 'bootsnap', '>= 1.4.4', require: false
gem 'jbuilder', '~> 2.11'
gem 'os', '~> 1.1', require: false
gem 'ostruct', '~> 0.6.0'

# Web server for development



# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development


group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 6.0'
  gem 'capybara', '>= 3.26'
  gem 'database_cleaner-active_record'
  gem 'webrick', '~> 1.8'
end


group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '>= 4.0.0'
  gem 'spring'
end
