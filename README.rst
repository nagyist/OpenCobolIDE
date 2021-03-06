OpenCobolIDE
------------
.. image:: https://travis-ci.org/OpenCobolIDE/OpenCobolIDE.png?branch=develop
    :target: https://travis-ci.org/OpenCobolIDE/OpenCobolIDE
    :alt: Travis-CI build status
    
.. image:: https://pypip.in/d/OpenCobolIDE/badge.png
    :target: https://crate.io/packages/OpenCobolIDE/
    :alt: Number of PyPI downloads

.. image:: https://pypip.in/v/OpenCobolIDE/badge.png
    :target: https://crate.io/packages/OpenCobolIDE/
    :alt: Latest PyPI version


OpenCobolIDE is a simple and lightweight cobol IDE based on the OpenCobol
compiler.


The software is written in Python using `PyQt4`_ and `pyQode`_

Features:
---------

- syntax highlighting
- code completion
- code folding
- navigable tree view of division, sections, paragraphs etc.
- calculates the offsets of selected record definitions
- compile as program (.exe) or as subprogram (.so)
- run the program from the editor
- also open text files
- cross platform: work on GNU/Linux and Windows


License
-------

OpenCobolIDE is released under the **GPL** version 3


Installation
------------

GNU/Linux
#########

From PPA
++++++++

There is now a PPA for Ubuntu and derivatives::

    $ sudo apt-add-repository ppa:open-cobol-ide/stable
    $ sudo apt-get update
    $ sudo apt-get install open-cobol-ide

From pip
++++++++
Run the following commands::

    sudo apt-get install python-qt open-cobol
    sudo easy_install OpenCobolIDE


Windows
#######

There is a windows installer available here: https://launchpad.net/cobcide/+download


Requirements
------------

The project depends on the following packages:

- `Python`_  *( >= 2.7 or >= 3.2)*
- `setuptools`_
- `PyQt4`_
- `OpenCobol`_
- `pyqode.core`_
- `pyqode.widgets`_
- `Pygments`_ **>= 1.6**
- `chardet`_ *(chardet2 if you are using python3)*
- `qdarkstyle`_


Resources
---------

-  `Downloads`_
-  `Source repository`_
-  `Issue tracker`_
-  `Documentation`_


Disclaimer
----------

I am by no way a cobol expert, I just had to work on a cobol project at school
with an awful IDE (NetExpress on a Windows Xp virtual machine). As I was writing
pyqode, I thought it would be nice to use it to make a simple cobol editor for
GNU/Linux.

I've only learnt COBOL 74 and the IDE has been designed with this standard in
mind. I don't plan to work with cobol at the moment nor to learn
a new standard but if you found a missing feature, feel free to open a feature
request. I'm always looking forward to make OpenCobolIDE better for the experts.

Your advice will be very appreciated!


Screenshots
-----------

* Home page:

.. image:: doc/source/_static/Home.png
    :align: center

* Editor:

.. image:: doc/source/_static/CompilerOutput.png
    :align: center


* Offset calculator

.. image:: doc/source/_static/OffsetCalculator.png
    :align: center


* Dark style support (based on `qdarkstyle`_ style sheet)

.. image:: doc/source/_static/DarkStyle.png
    :align: center


.. _qdarkstyle: https://github.com/ColinDuquesnoy/QDarkStyleSheet
.. _pyQode: https://github.com/pyQode/
.. _PyQt4: http://www.riverbankcomputing.co.uk/software/pyqt/download
.. _Downloads: https://github.com/OpenCobolIDE/OpenCobolIDE/releases
.. _Source repository: https://github.com/OpenCobolIDE/OpenCobolIDE/
.. _Issue tracker: https://github.com/OpenCobolIDE/OpenCobolIDE/issues?state=open
.. _`Documentation`: http://opencobolide.readthedocs.org/en/latest/
.. _chardet: https://pypi.python.org/pypi/chardet
.. _Pygments: http://pygments.org/
.. _pyqode.core: https://github.com/pyQode/pyqode.core/
.. _pyqode.widgets: https://github.com/pyQode/pyqode.widgets/
.. _OpenCobol: http://opencobol.org/
.. _setuptools: https://pypi.python.org/pypi/setuptools
.. _Python: http://python.org/
