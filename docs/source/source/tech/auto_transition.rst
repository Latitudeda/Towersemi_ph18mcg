auto_transition.py
====================

Define the transition between different waveguide types.

In towersemi_ph18mcg PDK, a taper will be added between two same type of waveguides with different width and a transition will be added between two different type of waveguides.

Users are allowed to define the taper and set ``DEFAULT`` to their own specific transition policy. Please see ``gpdk > components > transition`` for more examples.