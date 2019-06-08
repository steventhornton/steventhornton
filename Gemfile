source "https://rubygems.org"

source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "github-pages",
  github: 'UnderpantsGnome/pages-gem',
  branch: "paginate-v2",
  group: :jekyll_plugins

gem "jekyll-gist"
gem "jekyll"
gem 'jekyll-feed'
gem "rouge"
gem 'jekyll-compose', group: [:jekyll_plugins]
