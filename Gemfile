source 'https://rubygems.org'
ruby '2.3.1'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'devise_token_auth'
gem 'jbuilder', '~> 2.5'
gem 'pg', '~> 0.18'
gem 'puma', '~> 3.0'
gem 'rack-cors', require: 'rack/cors'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'

group :development, :test do
  gem 'factory_girl_rails'
  gem 'pry-byebug'
  gem 'pry'
  gem 'rspec-rails'
  gem 'shoulda-matchers'
end

group :development do
 gem 'listen', '~> 3.0.5'
 gem 'spring'
 gem 'spring-watcher-listen', '~> 2.0.0'
end
