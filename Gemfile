source('https://rubygems.org')

gemspec

gem 'google-protobuf', '~> 4.28'
gem 'rest-client'
gem 'app-info', '~> 3.2.0'

plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
