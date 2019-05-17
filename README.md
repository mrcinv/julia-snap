# Snapcraft configuration for julia

To build julia, first install [snapcraft](https://snapcraft.io/). Then simply run 

    $ cd julia-snap
    $ snapcraft
    
 Then install it by
 
    $ sudo snap install --classic --dangerous julia-mrcinv*.snap
    
 You can run julia with
 
    $ julia-mrcinv
       _       _ _(_)_     |  Documentation: https://docs.julialang.org
      (_)     | (_) (_)    |
       _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
      | | | | | | |/ _` |  |
      | | |_| | | | (_| |  |  Version 1.1.1 (2019-05-16)
     _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
    |__/                   |

    julia>
