source "https://rubygems.org"

gem "github-pages", group: :jekyll_plugins
gem "webrick", "~> 1.8"
gem "connection_pool", "2.5.0"

# Needed because Ruby 3.4 no longer ships bigdecimal as a default gem
gem "bigdecimal"

# Windows-specific timezone fix
install_if -> { Gem.win_platform? } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
