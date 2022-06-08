source "https://rubygems.org"

gem "github-pages", "~> 226", group: :jekyll_plugins
gem "jekyll-theme-cayman"

group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]

# Added this as a workaround mentioned here:
# https://github.com/jekyll/jekyll/issues/8523
gem "webrick", "~> 1.7"
