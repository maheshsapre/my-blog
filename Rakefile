#!/usr/bin/env rake
# Add your own tasks in files placed in lib/tasks ending in .rake,
# for example lib/tasks/capistrano.rake, and they will automatically be available to Rake.

require File.expand_path('../config/application', __FILE__)

MyBlog::Application.load_tasks


require 'rubygems'
# Install:
#  sudo gem install ci_reporter
gem 'ci_reporter'


./script/plugin install http://svn.codahale.com/rails_rcov

./script/plugin install http://github.com/troelskn/gemconf_plugin.git
