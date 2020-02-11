# Snapcraft configuration for julia

[![Snap Status](https://build.snapcraft.io/badge/mrcinv/julia-snap.svg)](https://build.snapcraft.io/user/mrcinv/julia-snap)

To build julia, first install [snapcraft](https://snapcraft.io/). Then simply run 

    $ cd julia-snap
    $ snapcraft
    
 Then install it by
 
    $ sudo snap install --classic --dangerous julia-mrcinv*.snap
    
 You can run julia with
 
    $ julia-mrcinv
                   _
       _       _ _(_)_     |  Documentation: https://docs.julialang.org
      (_)     | (_) (_)    |
       _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
      | | | | | | |/ _` |  |
      | | |_| | | | (_| |  |  Version 1.3.1 (2019-12-30)
     _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
    |__/                   |
    
    julia>

To be able to simply use `julia` to run the snap, you can use bash command alias

    alias julia='snap run julia-mrcinv'
