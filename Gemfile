source 'https://rubygems.org'

gem 'rails', '4.1.7'
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 2.0'
# gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'spring',        group: :development
gem 'bootstrap-sass', '~> 3.3.1'
gem 'autoprefixer-rails'

# here's a group, open it up, and here's what's inside of it, end.
# this group says to use the sqlite3 gem in dev and test
group :development, :test do
	gem 'sqlite3'
end

# this one says to use post gress in production
group :production do
	gem 'pg'
	gem 'rails_12factor'
end

# bundle exec rake doc:rails generates the API under doc/api
group :doc do
	gem 'sdoc', require: false
end
