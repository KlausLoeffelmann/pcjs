source 'https://rubygems.org'

# Use the GitHub Pages gem to manage dependencies
gem 'github-pages', group: :jekyll_plugins

# Additional Jekyll plugins that are compatible with GitHub Pages
gem 'jekyll-sitemap', group: :jekyll_plugins
gem 'jekyll-redirect-from', group: :jekyll_plugins
gem 'jekyll-include-cache', group: :jekyll_plugins

# Required for Jekyll server on Ruby 3.0+
gem 'webrick', '~> 1.7'

# Conditionally include 'wdm' gem only on Windows
if Gem.win_platform?
  gem 'wdm', '>= 0.1.0'
end
