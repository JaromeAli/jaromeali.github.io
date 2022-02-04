#after any changes to the Gemfile, execute bundle update!

source "https://rubygems.org"

gem 'wdm', '>= 0.1.0' if Gem.win_platform?

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem "github-pages"

group :jekyll_plugins do
 gem "jekyll-sitemap"
 gem "jekyll-seo-tag"
end

gem "webrick", "~> 1.7"
