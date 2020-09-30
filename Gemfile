source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!

# Sets Jekyll version
gem "jekyll", "~> 3.8.5" #, "~> 4.1.1"
# NB: v4.1.1 doesn't work with GitHub Pages - downgraded to v3.8.5 until support provided

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Sets compatibility for GitHub Pages
gem "github-pages", group: :jekyll_plugins

# Gems for feed-related plugins
plugins:
  - jekyll-sitemap
  - jekyll-feed
  - jekyll-seo-tag

# Theme-related stuffs
# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.5"
# gem "just-the-docs"
# gem "minimal-mistakes-jekyll"
