require 'rspec/core/rake_task'
require 'yaml'
require 'csv'
require_relative 'scripts/new_cves'

desc 'Run the specs by default'
task default: :spec

RSpec::Core::RakeTask.new(:spec)

task :new_cves do
  NewFFmpegCVEs.new().run
end
