source "https://rubygems.org"

# The github-pages gem keeps local builds close to GitHub Pages' supported Jekyll environment.
gem "github-pages", group: :jekyll_plugins

# Windows and JRuby may need this dependency for local builds.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Required by newer Ruby versions for some Jekyll dependencies.
gem "webrick", "~> 1.8"
