source "https://rubygems.org"

gem "rails", "~> 8.0.0.beta1"
gem "propshaft"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem 'devise', '~> 4.9', '>= 4.9.4'
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "turbo-rails"
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"

gem "bootsnap", require: false
gem "kamal", ">= 2.0.0.rc2", require: false
gem "thruster", require: false


group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"

  gem "brakeman", require: false

  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
  gem "sqlite3", ">= 2.1"
end

group :production to
gem "pg", "~> 1.5", ">= 1.5.9"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
