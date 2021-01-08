source "https://rubygems.org"

ruby File.read('.ruby-version').strip

gem "rake"
gem "github-pages"

gem "webrick" # Ruby 3 doesn't include this by default and Jekyll needs it. At some point we can drop this.

group :test do
  gem "jekyll-test"
end
