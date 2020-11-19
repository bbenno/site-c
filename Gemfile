source 'https://rubygems.org'

ruby RUBY_VERSION

gem 'jekyll', '~> 4.1'

group :jekyll_theme do
  gem 'minima'
end

group :jekyll_plugins do
  gem 'jekyll-asciidoc'
end

# Windows does not include zoneinfo files
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem 'tzinfo', '~> 1.2'
  gem 'tzinfo-data'
  gem 'wdm', '>= 0.1.0'
end
