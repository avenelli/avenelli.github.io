source "https://rubygems.org"

#gem "jekyll", "~> 3.0"
gem "github-pages", group: :jekyll_plugins
gem "minimal-mistakes-jekyll"
gem "jekyll-sitemap"
gem "jekyll-gist"
gem "octopress"
gem "sassc"

group :jekyll_plugins do
   gem "jekyll-paginate"
   gem "jekyll-feed"
   gem "jekyll-include-cache"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
   gem "tzinfo"
   gem "tzinfo-data"




