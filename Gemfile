source "https://rubygems.org"

# Use the latest stable Jekyll version
gem "jekyll", "~> 4.4"

# Your theme (uncomment/change if you have a theme)
# gem "minimal-mistakes-jekyll"

# Plugins you use
group :jekyll_plugins do
  gem "jekyll-remote-theme"
  gem "jekyll-paginate"
  gem "jekyll-sitemap"
  gem "jekyll-feed"
  gem "jemoji"
  gem "jekyll-include-cache"
end

# Windows and JRuby support
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for Windows
gem "wdm", "~> 0.1.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb on JRuby
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
