source 'http://rubygems.org'

gem 'rails', '~> 3.2' # path: '../rails'
gem 'sqlite3-ruby', :require => 'sqlite3'
gem 'nifty-generators'
gem "activeadmin", path: '../activeadmin' # , ref: '70ad27c7d8112e866c291437825eadd03313bc9d' # 70ad27c predates PR-3486
gem 'cocoon', path: '../cocoon'
gem 'devise', '~> 3.2'
gem "faker"
gem 'formtastic', path: '../formtastic'
gem 'newrelic_rpm', '3.1.1'
gem 'hoptoad_notifier', '2.4.11'
gem 'rack-throttle'

group :development do
  gem 'mechanize'
end

group :production do
  gem 'unicorn'

  # Enable gzip compression on heroku, but don't compress images.
  gem 'heroku-deflater'

  # Heroku injects it if it's not in there already
  gem 'rails_12factor'
end
