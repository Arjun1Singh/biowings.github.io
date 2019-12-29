source "https://rubygems.org"

gem "minimal-mistakes-jekyll"

group :jekyll_plugins do
    gem "jekyll", ">= 3.6", "< 5.0"
    gem "jekyll-paginate", "~> 1.1"
    gem "jekyll-sitemap", "~> 1.3"
    gem "jekyll-gist", "~> 1.5"
    gem "jekyll-feed", "~> 0.1"
    gem "jekyll-include-cache", "~> 0.1"
end

gem "bundler"
gem "rake", "~> 10.0"

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
    gem "tzinfo", "~> 1.2"
    gem "tzinfo-data"
  end
# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?