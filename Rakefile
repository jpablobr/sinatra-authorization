require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gemspec|
    gemspec.name = "jpablobr-sinatra-authorization"
    gemspec.summary = "jpablobr-sinatra-authorization HTTP Authorization helpers for Sinatra."
    gemspec.description = "jpablobr-sinatra-authorization HTTP Authorization helpers for Sinatra."
    gemspec.email = "xjpablobrx@gmail.com"
    gemspec.homepage = "http://github.com/jpablobr/sinatra-authorization"
    gemspec.authors = ["Jose Pablo Barrantes"]
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install jeweler -s http://gemcutter.org"
end

Dir["#{File.dirname(__FILE__)}/tasks/*.rake"].sort.each { |ext| load ext }
