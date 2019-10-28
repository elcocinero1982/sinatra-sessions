ENV["SINATRA_ENV"] ||= "development"

require_relative './config/environment'

# Type `rake -T` on your command line to see the available rake tasks.
require './config/environment'
require 'sinatra/activerecord/rake'
task :console do
  Pry.start
end