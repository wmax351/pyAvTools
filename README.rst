===========================================
MakerPlane Aviation Module Tool Kit
===========================================

Copyright (c) 2019 MakerPlane

This is an experimental system, and is not suited for primary or backup flight/engine instrumentation or navigation. Use at your own risk.

pyAvTools is an open source aviation tool kit, providing useful modules for Python based
Aviation apps, including:
    * Data management package for charting objects
    * Flight Information eXchange (FIX) database module
    * A hard-button based user interface layer utilizing Qt (no keyboard or mouse required)
        * Uses a rotary encoder + push buttons
        * NumberWidget (Show/Change a number)
        * ChoiceWidget (Show/Change a radio-button style section)
        * SelectMenuWidget (Show/Change a menu style section)
        * FIXDisplay (Show a collection of FIX database items)
    * Others for future consideration

Installation
------------

Begin by cloning the Git repository

::

    git clone git@github.com:makerplane/pyAvTools.git

or

::

    git clone https://github.com/makerplane/pyAvTools.git 


If you'd like to install the program permanently to your system or into a virtualenv you
can issue the command...

::

  sudo pip3 install .

from the root directory of the source repository.  **Caution** This feature is still
in development and may not work consistently.

Requirements
------------
