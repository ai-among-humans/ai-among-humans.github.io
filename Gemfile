source "https://rubygems.org"

# Pin to GitHub Pages’ stack (see https://pages.github.com/versions/) — much
# smaller than the `github-pages` meta-gem, so `bundle install` uses less RAM.
gem "jekyll", "3.10.0"
gem "kramdown-parser-gfm"
gem "minima", "2.5.1"
gem "webrick", "~> 1.8"
# Ruby 3.4+ — these stdlib pieces are default gems now; older Jekyll/Liquid still require them.
gem "base64"
gem "bigdecimal"

group :jekyll_plugins do
  gem "jekyll-feed", "0.17.0"
  gem "jekyll-seo-tag", "2.8.0"
end
