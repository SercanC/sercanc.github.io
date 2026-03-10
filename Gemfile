source "https://rubygems.org"

# GitHub Pages gem - includes Jekyll and all supported plugins
gem "github-pages", group: :jekyll_plugins

# Optional: for local development only
group :jekyll_plugins do
  gem "jekyll-feed"
  gem "jekyll-seo-tag"
end

# Windows-specific gems
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]
