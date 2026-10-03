# Only needed for previewing the site on your own machine.
# GitHub Pages ignores this file and builds the site itself.

source "https://rubygems.org"

# Pins Jekyll and every plugin to the exact versions GitHub Pages runs,
# so local previews match the deployed site.
gem "github-pages", group: :jekyll_plugins

# Ruby 3.0+ dropped webrick from the stdlib; jekyll serve needs it.
gem "webrick", "~> 1.8"

# Windows: timezone data and a faster file watcher.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.1"
end
