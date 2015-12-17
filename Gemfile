source 'https://rubygems.org'
ruby '2.2.2'
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']

gem 'jekyll'
gem 'kramdown'
gem 'rack-jekyll'
gem 'rake'
gem 'puma'