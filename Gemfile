#source 'http://mirror1.prod.rhcloud.com/mirror/ruby/'
source 'http://rubygems.org'

gem 'rails', '~> 3.2.12'
gem 'authlogic'
gem 'jquery-rails', '2.0.1'

group :production do
	gem 'mysql2'
end

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
	gem 'rspec', '>= 2.0.0.beta.20'
  gem 'rspec-rails', '>= 2.0.0.beta.20'
	gem 'autotest'
	gem 'webrat'
	gem 'annotate'
	gem 'sqlite3'
end
