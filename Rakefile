require "bundler/gem_tasks"

require 'rspec/core'
require 'rspec/core/rake_task'

RSpec::Core::RakeTask.new(:spec) do |spec|
  spec.pattern = FileList['spec/**/*_spec.rb']
  #spec.rspec_opts = '--order random' need to fix some test to make this randow :( bad tests!
end

desc 'Default: Run all specs.'
task :default => :spec