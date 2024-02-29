source "https://rubygems.org"

# Use GitHub Pages only to avoid version conflicts
gem "github-pages", group: :jekyll_plugins

# If you want to use a theme or other plugins, you can include them here
# Make sure any plugins or themes you add are compatible with GitHub Pages
group :jekyll_plugins do
  # For example, if 'jekyll-feed' is compatible with your version of 'github-pages', you can include it
  # gem "jekyll-feed"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library. Only include these gems on Windows platforms.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows, include only on Windows platforms.
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# This section is specific to JRuby, include only if you're using JRuby.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]
