source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "~> 3.8.3"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "jekyll-theme-open-project", "~> 2.0.13"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-seo-tag"
  gem "jekyll-sitemap"
  gem "jekyll-data"
  gem "jekyll-asciidoc"
  gem "git"
  gem "jekyll-theme-open-project-helpers", "~> 2.0.13"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0" if Gem.win_platform?

# For testing generated HTML pages and links
gem "rake"
gem "html-proofer"
