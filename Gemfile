source 'http://rubygems.org'

gem 'rails', '3.1.1'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

group :development, :test do
  gem 'sqlite3'
end
group :production do
  # gems specifically for Heroku go here
  gem "pg"
end

gem 'jquery-rails'

gem 'mercury-rails', git: 'https://github.com/jejacks0n/mercury.git', ref: 'a2b16bcdc9'

