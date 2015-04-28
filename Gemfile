source 'https://rubygems.org'

group :development do
  gem 'guard', '~> 2.11'
  gem 'guard-kitchen'
  gem 'guard-foodcritic'
  gem 'guard-rspec'
  gem 'guard-rubocop'
  gem 'rake'
  gem 'rb-fsevent'
end

group :style do
  gem 'foodcritic', '~> 4.0'
  gem 'rubocop',    '~> 0.30.1'
end

group :unit do
  gem 'berkshelf', '~> 3.2.0'
  gem 'chefspec',  '~> 4.2.0'
  gem 'coveralls', '~> 0.8.1', require: false
end

group :kitchen_cloud do
  gem 'kitchen-digitalocean'
  gem 'kitchen-ec2'
  gem 'kitchen-gce'
  gem 'kitchen-joyent'
end

group :kitchen_common do
  gem 'test-kitchen', '~> 1.3'
end

group :kitchen_docker do
  gem 'kitchen-docker', '~> 2.1.0'
end

group :kitchen_vagrant do
  gem 'kitchen-vagrant', '~> 0.16.0'
end
