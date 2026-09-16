PDK structure
======================

Process Design Kit (PDK) is a tool for designated users to generate circuit layouts based on Tower Semiconductor design rules and technology settings.

``towersemi_ph18mcg`` package includes four subfolders: ``components``, ``examples``, ``schematic``, ``symbols``, ``technology``, and ``util``.

* ``components``

    * Fixed cells: All fixed cells, including ``Cross``, ``Directional Coupler``, ``Grating Coupler``, ``MultiMode Interferometer``, ``Phase Shifter``, ``Photodiode``, ``S bend``, ``Towersemi_bend``, ``Towersemi_taper``, ``Y junction``, ``Transition`` and ``Towersemi_wg`` are named and designed by **Tower Semiconductor** and cannot be changed.

    * Parametrized cells (PCells): Designed by **LDS**, including ``Bend``, ``Bond Pad``, ``Taper`` and ``Straight``. Please see ``gpdk > components`` for more designed components by **LDS**.

* ``examples``

    * ``link.py`` : Test circuit to test if auto routing, and auto link function works normally under the PDK setting. Please see ``gpdk > examples`` for more circuit examples.

* ``schematic``

    * Store the schematic setting for linking PhotoCAD to AdvancedSDL.

* ``symbols``

    * Store the symbol setting for linking PhotoCAD to AdvancedSDL.

* ``technology``

    * Store the technology setting which matched the Tower Semiconductor design rules. We recommend users not to change the settings in technology folder.

    * See chapter ``Technology setting`` for more specific definition.

* ``util``

    * Useful functions when generating circuit layouts.

    * Please see **PhotoCAD** online manual for more information.

* ``layers.lyp`` : This file allows layout tools e.g. KLayout to recognize the layer information when displaying gds file to the layout tool.

    .. image:: ../images/lyp1.png
    .. image:: ../images/lyp2.png

