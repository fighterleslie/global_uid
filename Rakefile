require 'bundler/setup'
require 'bundler/gem_tasks'
require 'wwtd/tasks'
require 'bump/tasks'
require 'rake/testtask'

task :default => 'wwtd:local'

Rake::TestTask.new(:test) do |test|
  test.pattern = 'test/**/*_test.rb'
  test.verbose = true
end
