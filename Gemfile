# Gemfile for ~/src/synchromesh/pub/blog
#

source 'https://rubygems.org'
gem 'octopress'
# gem 'octopress-solarized'
gem 'octopress-deploy'

# Ref: http://jekyllrb.com/docs/github-pages/
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)
gem 'github-pages', versions['github-pages']

# End of Gemfile
