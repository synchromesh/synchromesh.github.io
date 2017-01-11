# Gemfile for ~/src/synchromesh/pub/blog
#
# 11 Jan 17 JDP
# Upgrading to Jekyll 3.3, Ruby 2.3 etc. as per
# https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/
#
# Note that the GitHub instructions are different to the Jekyll
# instructions at http://jekyllrb.com/docs/github-pages/.

# Ref: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/#step-2-install-jekyll-using-bundler
source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins

gem 'octopress'
gem 'octopress-deploy'

# Ref: http://jekyllrb.com/docs/github-pages/
# 11 Jan 17 JDP Commenting these out for now.
# require 'json'
# require 'open-uri'
# versions = JSON.parse(open('https://pages.github.com/versions.json').read)
# gem 'github-pages', versions['github-pages']

# For JPKB - allow Jekyll to process Org pages.
group :jekyll_plugins do
   gem 'org-ruby'
end

# End of Gemfile
