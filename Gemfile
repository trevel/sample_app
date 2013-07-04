source 'https://rubygems.org'
ruby '1.9.3'

require 'rbconfig'
gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'
gem 'bootstrap-sass', '2.3.2.0'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.1.2'
gem 'will_paginate', '3.0.4'
gem 'bootstrap-will_paginate', '0.0.9'

# Use sqlite3 as the database for Active Record
group :development, :test do
	gem 'sqlite3', '1.3.7'
	gem 'rspec-rails', '2.13.1'
	gem 'guard-rspec', '2.5.0'
	gem 'spork-rails', github: 'railstutorial/spork-rails'
	gem 'guard-spork', '1.5.0'
	gem 'childprocess', '0.3.6'
end

group :test do
	gem 'selenium-webdriver', '2.0.0'
	gem 'capybara', '2.1.0'
	gem 'factory_girl_rails', '4.2.0'
	gem 'cucumber-rails', '1.3.0', :require => false
	gem 'database_cleaner', github: 'bmabey/database_cleaner'
	#Windows specific
	gem 'rb-notifu', '0.0.4'
	gem 'win32console', '1.3.2'
end

gem 'sass-rails', '4.0.0'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.0'
gem 'jquery-rails', '2.2.1'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
	gem 'sdoc', '0.3.20', require: false
end

group :production do
	gem 'pg', '0.15.1'
end
