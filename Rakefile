# -*- coding: utf-8 -*-
require "bundler/gem_tasks"
$:.unshift("/Library/RubyMotion/lib")
require 'motion/project/template/ios'
require 'bundler'
Bundler.require(:default)

require 'motion-cocoapods'

require 'motion_model'
#require 'motion_model/array'
#require 'motion_model/sql'
#require 'motion_model/fmdb'

Motion::Project::App.setup do |app|
  # Use `rake config' to see complete project settings.
  app.name = 'MotionModel'
  app.delegate_class = 'FakeDelegate'
  app.detect_dependencies = false

  app.pods do
    pod 'FMDB', '2.1'
  end
end
