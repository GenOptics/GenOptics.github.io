#after any changes to the Gemfile, execute bundle update!
source "https://rubygems.org"
gemspec

# Delete the following lines if not on Windows: 
# Performance-booster for watching directories on Windows
gem "wdm", ">= 0.1.0" if Gem.win_platform?

# These lines were added after Jekyll Github Action was first used:
gem 'jekyll'
gem 'jekyll-feed'
gem 'jekyll-sitemap'
gem 'jekyll-seo-tag'
gem 'jemoji'
gem 'jekyll-readme-index'
gem "jekyll-remote-theme"
gem "kramdown-parser-gfm"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-sitemap"
  gem "jekyll-scholar"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
