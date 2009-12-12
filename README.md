# sequel_plus

This library starts the collection of plugins and possibly extension I assemble for the Ruby Sequel 
ORM.  

Currently, it only contains a plugin for Trees to mimic the Rails acts_as_tree plugin.

NOTE:  Authors of other plugins and extensions for Sequel are welcome to contact me for inclusion
of your plugin and extension to this project.

Released under MIT license.

# For the Impatient

This gem is released to gemcutter.  Rubyforge is not utilized. 

  gem install sequel_plus

And then, in your project:

  require 'sequel'
  require 'sequel_plus'

  class Node < Sequel::Model
    plugin :tree
  end
  
# Note on Patches/Pull Requests
 
* First release!

# Copyright

Copyright 2009 Michael Lang.  All rights reserved.
Released under MIT license.  See LICENSE for details.
