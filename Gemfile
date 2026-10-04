source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

gem 'jekyll'

group :jekyll_plugins do
  # >= 228 pulls liquid 4.0.4 (Ruby 3.2+ safe). Unpinned github-pages +
  # jekyll-include-cache otherwise resolves to github-pages 222 / liquid 4.0.3,
  # which crashes with undefined method `tainted?`.
  gem 'github-pages', '>= 228'
  gem 'jekyll-remote-theme'
  gem 'jekyll-include-cache'
end

# gem "rails"
