require 'rubygems'
require 'rake'
require 'echoe'

#version = File.read( 'VERSION' ) rescue "0.0.42_bugged"

Echoe.new('r', '0.0.1' ) do |p|
  p.description    = "My second gem, and most minimalistic."
  p.url            = "http://github.com/palladius/r"
  p.author         = "Riccardo C."
  p.email          = "['p','ll','diusbonton@gm','il.com'].join('a')"
  p.ignore_pattern = [
    "docs/*", 
    "script/*", 
    "tmp/*", "tmp/*/*", "tmp/*/*/*",
#    "images/*/*/*", "images/*/*", 'images', 
    "private/*",
    "HISTORY"
  ]
  p.development_dependencies = [ ]
end