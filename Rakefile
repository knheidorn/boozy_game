require_relative './config/environment'

desc 'Run the CLI'
task :run do
    CLI.run
end

desc 'starts a console'
task :console do
  ActiveRecord::Base.logger = Logger.new(STDOUT)
  Pry.start
end
