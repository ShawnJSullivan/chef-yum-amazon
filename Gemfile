source 'https://rubygems.org'

gem 'berkshelf',  '~> 2.0'
gem 'chefspec',   '>= 3.1'
gem 'foodcritic', '>= 3.0'
gem 'rubocop'

group :integration do
  gem 'test-kitchen', '~> 1.0'
  gem 'kitchen-vagrant', '~> 0.11'
  gem 'kitchen-digitalocean'
  gem 'kitchen-ec2'
end

group :development do
  gem 'fauxhai'
  gem 'guard'
  gem 'guard-rspec'
  gem 'guard-kitchen'
  gem 'guard-foodcritic', '>= 1.0'
end
