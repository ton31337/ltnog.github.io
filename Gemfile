source 'https://rubygems.org'

require 'json'
require 'open-uri'
require 'uri'

versions = JSON.parse(::URI.open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'rake'
gem 'jekyll-feed'
gem 'minimal-mistakes-jekyll'

gem 'rouge'
