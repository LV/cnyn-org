#!/usr/bin/env ruby

require 'html-proofer'
HTMLProofer.check_directory("./_site").run

require 'rspec/core/rake_task'
task :default => :spec
RSpec::Core::RakeTask.new
