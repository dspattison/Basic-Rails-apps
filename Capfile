require 'rubygems'
load 'deploy'

set :scm, :git
set :application, "Basic-Rails-Application"
set :repository, 'git@github.com:dspattison/Basic-Rails-apps.git'

role :web, 'ec2-50-16-139-242.compute-1.amazonaws.com'
role :app, 'ec2-50-16-139-242.compute-1.amazonaws.com'

ssh_options[:user] = "ubuntu"
ssh_options[:keys] = ["#{ENV['HOME']}/.ec2/davidp.pem"]

set :use_sudo, false 

namespace :deploy do
  task :restart do 
  end
end
