# frozen_string_literal: true

source "https://rubygems.org"

gemspec

gem "webrick"

gem "sassc", "~> 2.4"
gem "jekyll-sass-converter", "~> 2.0"

gem "html-proofer", "~> 5.0", group: :test

platforms :windows, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.2.0", :platforms => [:windows]
