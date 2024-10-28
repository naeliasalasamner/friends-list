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

gem "bootsnap", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
  gem "sqlite3", ">= 2.1"
end

group :development do
  gem "web-console"
end

group :production do
  gem "pg", ">= 1.1"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
