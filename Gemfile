source 'https://rubygems.org'

gemspec

group :development do
  gem 'nokogiri',      '~> 1.5.0', :group     => :test
  gem 'jruby-openssl', '~> 0.7.4', :platforms => :jruby # For WebMock.

  gem 'redcarpet',                 :platforms => :ruby
  gem 'yard'
  gem 'rubysl',                    :platforms => :rbx
  gem 'rubysl-resolv', '~> 2.0',   :platforms => :rbx
  gem 'racc',                      :platforms => :rbx
gem 'rails_12factor', group: :production
end


gem 'rails', '3.2.12'
gem 'bundler', '1.1.5'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails'
