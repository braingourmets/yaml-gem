# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be
# available to Rake.

task :default => [:test]

task test: [:rubocop]

task :rubocop do
  sh 'rubocop .'
end
