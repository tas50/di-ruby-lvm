# -*- ruby -*-

require 'rubygems'
require 'hoe'
$:.unshift(File.dirname(__FILE__) + "/lib")
require 'lvm'

Hoe.new('ruby-lvm', LVMWrapper::VERSION) do |p|
  p.developer('Matthew Kent', 'matt@bravenet.com')
  p.extra_deps << ['popen4', '>= 0.9.6']
end

# vim: syntax=Ruby