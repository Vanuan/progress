require 'rubygems'
require 'rake'
require 'rake/clean'
require 'fileutils'
require 'echoe'

load 'tasks/rspec.rake'

task :default => :spec
task :test

require File.dirname(__FILE__) + '/lib/progress'

Echoe.new('progress', Progress::VERSION) do |p|
  p.author = "toy"
  p.summary = "A library to show progress of long running tasks."
end
