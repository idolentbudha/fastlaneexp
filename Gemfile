source 'https://rubygems.org'

# You may use http://rbenv.org/ or https://rvm.io/ to install and use this version
# ruby File.read(File.join(__dir__, '.ruby-version')).strip
ruby '3.2.0'

gem 'cocoapods', '~> 1.11', '>= 1.11.3'

gem 'fastlane'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
