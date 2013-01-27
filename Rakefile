require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "toto"
    gem.summary = %Q{a quick trip around the blogosphere}
    gem.description = %Q{a sweet blogging engine}
    gem.email = "josephmclaughlin@me.com"
    gem.homepage = "http://github.com/mclaughj/toto"
    gem.authors = ["mclaughj"]
    gem.add_development_dependency "riot"
    gem.add_dependency "builder"
    gem.add_dependency "rack"
    if RUBY_PLATFORM =~ /win32/
      gem.add_dependency "maruku"
    else
      gem.add_dependency "rdiscount"
    end
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

#require 'rake/testtask'
#Rake::TestTask.new(:test) do |test|
#  test.libs << 'lib' << 'test'
#  test.pattern = 'test/**/*_test.rb'
#  test.verbose = true
#end
#
#task :test => :check_dependencies
task :default => :begin
