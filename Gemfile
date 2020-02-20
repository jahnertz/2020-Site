# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

# gem "rails"
gem "jekyll", "~> 4.0.0"
group :development do
  install_if -> { ENV['JEKYLL_ENV']!="production" } do
    gem "jekyll-theme-tekhaus", path: "../jekyll-theme-tekhaus", github: "jahnertz/jekyll-theme-tekhaus"
  end
end
