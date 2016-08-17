# If you have OpenSSL installed, we recommend updating
# the following line to use "https"
ruby '2.2.0'
source 'http://rubygems.org'

gem "middleman", "~>4.1.10"

# Live-reloading plugin
gem "middleman-livereload", "~> 3.1.0"
gem 'middleman-thumbnailer', :git => 'git://github.com/nhemsley/middleman-thumbnailer.git'

# For faster file watcher updates:
# gem "wdm", "~> 0.1.0") # Windows

# Cross-templating language block fix for Ruby 1.8
platforms :mri_18 do
  gem "ruby18_source_location"
end
