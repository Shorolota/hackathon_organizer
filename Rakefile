# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require_relative 'config/application'
require 'rubocop/rake_task'
require 'rspec/core/rake_task'

Rails.application.load_tasks

RuboCop::RakeTask.new(:rubocop)
RSpec::Core::RakeTask.new(:rspec)

#desc "Run all tests"
#task spec: [:rspec, :rubocop]
