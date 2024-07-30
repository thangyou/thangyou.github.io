# frozen_string_literal: true

source "https://rubygems.org"

gemspec

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw]

gem "jekyll-coffeescript"
gem "jekyll-default-layout"
gem "jekyll-github-metadata"
gem "jekyll-optional-front-matter"
gem "jekyll-readme-index"
gem "jekyll-titles-from-headings"
gem "jekyll-relative-links"


group :test do
  gem "html-proofer", "~> 5.0"
end

group :jekyll_plugins do
  gem 'jekyll-seo-tag', '~> 2.8.0'
end
