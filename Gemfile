source "https://rubygems.org"

# Use GitHub Pages, which will manage Jekyll version for you
gem "github-pages", group: :jekyll_plugins

# Theme
gem "no-style-please"

# Jekyll Plugins
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-remote-theme" # Enables remote themes
end

# Windows and JRuby compatibility
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` to `v0.6.x` for JRuby builds
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]
