require_relative './config/environment'
#makes the rake -T commands available

require 'sinatra/activerecord/rake'

desc "Runs a Pry console"
task :console do
  # This line turns on logging of the SQL generated by Active Record
  ActiveRecord::Base.logger = Logger.new(STDOUT)
  
  # Open a Pry session
  Pry.start
end
