source 'http://rubygems.org'

gemspec

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 3.2.0'
  gem 'uglifier', '>= 1.0.3'
  gem 'compass', '0.12.alpha.0'
  gem 'bootstrap-sass', '2.0.1'
end

group :development do
  gem 'awesome_print', '~> 0.4.0', :require => 'ap'
  gem 'rails_best_practices'
end

platforms :jruby do
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'activerecord-jdbcmysql-adapter'
  gem 'jruby-openssl'
  gem 'trinidad'
end

platforms :ruby do
  gem 'pg'
  gem 'mysql2', '~> 0.3.0'
end

