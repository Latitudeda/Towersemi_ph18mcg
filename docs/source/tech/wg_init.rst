__init__.py
===================

Define the WG class which consists of ``Strip.C.WIRE_TE``, ``Strip.C.WIRE_TM``, ``Strip.O.WIRE_TE``, ``Strip.O.WIRE_TM``, ``Ridge.C.WIRE_TE``, ``Ridge.C.WIRE_TM``, ``Ridge.O.WIRE_TE``, ``Ridge.O.WIRE_TM``, ``SiN_strip.C.WIRE_TE``, ``SiN_strip.C.WIRE_TM``, ``SiN_strip.O.WIRE_TE`` and ``SiN_strip.O.WIRE_TM`` classes. The width of the waveguide is set here according the parameters in ``constant.py`` file. **PhotoCAD** also supports CD bias control of the waveguide width. The CD bias setting can be implemented in ``strip.py``, ``ridge.py`` and ``SiN_strip.py`` .

.. table:: Waveguide Type Table

    ================================  ==========================================
    WAVEGUIDE_TYPE                    PARAMETERS
    ================================  ==========================================
    `TECH.WG.Strip.C.WIRE_TE`         core_width=0.4500
    `TECH.WG.Strip.C.WIRE_TM`         core_width=0.4500
    `TECH.WG.Strip.O.WIRE_TE`         core_width=0.4000
    `TECH.WG.Strip.O.WIRE_TM`         core_width=0.4000
    `TECH.WG.Ridge.C.WIRE_TE`         core_width=0.4500, cladding_width=4.4500
    `TECH.WG.Ridge.C.WIRE_TM`         core_width=0.4500, cladding_width=4.4500
    `TECH.WG.Ridge.O.WIRE_TE`         core_width=0.4500, cladding_width=4.4500
    `TECH.WG.Ridge.O.WIRE_TM`         core_width=0.4500, cladding_width=4.4500
    `TECH.WG.SiN_strip.C.WIRE_TE`     core_width=0.7000
    `TECH.WG.SiN_strip.C.WIRE_TM`     core_width=0.8000
    `TECH.WG.SiN_strip.O.WIRE_TE`     core_width=0.7000
    `TECH.WG.SiN_strip.O.WIRE_TM`     core_width=0.7000
    ================================  ==========================================

