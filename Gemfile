source "https://rubygems.org"

gem "jekyll", "~> 3.8.6"


# Používá společné thema to je stále ve vývoji tj změny mužou být velké a je třeba důkladně testovat jestli se věci nerozbíjejí.
# Comment this line for local development.
gem "jekyll-theme-pirati", "~>7.7.1"

# Uncomment this line for local development.
# gem "jekyll-theme-pirati", github: "pirati-web/jekyll-theme-pirati", branch: "master"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.6"
  gem "jekyll-paginate"
  gem "jekyll-redirect-from"
  gem "jekyll-sitemap"
  # gem "github-pages"
  gem "jekyll-assets", "3.0.11", group: :jekyll_plugins
end

group :development, :test do
  gem "html-proofer"
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem "json" # For gem building
gem 'sprockets', '4.0.0.beta8'
gem 'uglifier', '~> 4.0.0'
gem "mini_magick"
gem "autoprefixer-rails"
gem "image_optim"
gem "image_optim_bin" # Optional
gem "image_optim_pack"
# Make sure watch mode works A-OK on Windows too
gem "wdm", "~> 0.1.1" if Gem.win_platform?
