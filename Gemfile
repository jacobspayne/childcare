source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=childcare

gem "carrierwave"

gem 'rails', '4.0.2'
gem 'bootstrap-sass', '2.3.2.0'
gem 'jquery-ui-rails'

# encrypted password plugin
gem 'bcrypt-ruby', '3.1.2'

gem 'rails3-jquery-autocomplete', '1.0.12'

# only used in development and test environments
group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.13.1'
end

# only used in production environment
group :production do
	# postgresql database
	gem 'pg', '0.15.1'
  
  # only needed if we deploy to heroku
  # gem 'rails_12factor', '0.0.2'
end

gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end