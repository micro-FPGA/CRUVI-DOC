CRUVI Design Guide
==================

CRUVI specification https://github.com/micro-FPGA/CRUVI/blob/master/docs/CRUVI_Specification.pdf

space 

`CRUVI specification <https://github.com/micro-FPGA/CRUVI/blob/master/docs/CRUVI_Specification.pdf>`_


Mechanical
----------

All measurements are in mm except module to module spacing.

Module spacing: module-to-module spacing is fixed 900 mil (same as PMoD)

Module max width: 22mm this allows 0.86 mm between max width installed modules


Connectors
~~~~~~~~~~

Board-to-Board mating height: 5 mm both for LS as for HS connectors. Use only connectors with correct height:

+------------------------+--------------------+----------------------+
| Connector Type         | Carrier/Base       | Module/Function      |
+========================+====================+======================+
| HS High Speed          | SS4-30-3.50-L-D-K  | ST4-30-1.50-L-D-P    |
+------------------------+--------------------+----------------------+
| LS Low Speed           | CLT-106-02-F-D-A-K | TMMH-106-04-F-DV-A-M |
+------------------------+--------------------+----------------------+

FMC Compatibility
~~~~~~~~~~~~~~~~~

CRUVI modules designed as low profile and with FMC compatibility will fit inside standard FMC mezzanine module:

.. image:: CR00061-3D.png

FMC to CRUVI adapter, two single width CRUVI modules installed.

For evaluation and testing CRUVI connectors can be on the other side of the FMC in that case all CRUVI modules would fit.

.. image:: CR00062-3D.png

PMoD Compatibility
~~~~~~~~~~~~~~~~~~
CRUVI LS maps 1:1 to-from PMoD only restriction is that PMoD as host would not deliver 5V to CRUVI.



Schematic/PCB
-------------

Altium Designer
~~~~~~~~~~~~~~~

Single width module with SMA connectors:

.. image:: CR00009-01-3D.png

This template should be used for single wide modules. SMA connectors are placed for FMC compatible front bezel.

KiCAD
~~~~~

WiP

Eagle
~~~~~

WiP









