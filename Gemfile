source :rubygems

gem 'activerecord', git: 'https://github.com/rails/rails.git', branch: '3-2-stable'
gem 'activesupport', git: 'https://github.com/rails/rails.git', branch: '3-2-stable'
gem 'fuzzy-string-match_pure', require: 'fuzzystringmatch/pure'
gem 'geocoder'
gem 'redis'
gem 'uuid'

group :importer do
  gem 'sequel'
end

group :exporter do
  gem 'sequel'
  gem 'sqlite3'
end

group :api do
  gem 'sinatra'
end

group :deviceapi do
  gem 'sinatra'
end

group :test do
  gem 'factory_girl'
  gem 'rack-test'
end

platforms :mri, :rbx do
  gem 'pg'
  gem 'yajl-ruby', require: ['yajl', 'yajl/json_gem']
end