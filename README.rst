Self-contained Python packages of Regina
========================================

The program `Regina`_ is a powerful tool for studying low-dimensional
topology. It comes with a full `Python`_ interface that lets one
interact with it programmatically without writing any C++ code. Our
goal here is to provide self-contained binaries ("wheels") of Regina's
Python package that can be installed in seconds from Python's `PyPI`_
package repository using `pip`.

The current version is somewhat experimental and is based on a
pre-release version of Regina; it is offered for macOS (10.14 and
newer) and Linux, but not Windows. To try it out, do::

  python3 -m pip install --user --pre regina
  python3 -m regina.test

For more on using Regina in Python see the `main docs`_.

These binaries are produced and maintained by Marc Culler, Nathan
Dunfield, and Matthias Goerner, though of course 99.9% of the code and
credit is due to the Ben Burton and the other authors of Regina
itself. This project evolved out of Goerner's `sageRegina`_
but works both with and without `SageMath`_. To install and test in
SageMath do::

  sage -pip install --user --pre regina
  sage -python -m regina.test

Please report any technical issues on the `tracker`_ devoted to this
repackaging of Regina.


License
-------

Copyright Ben Burton, Ryan Budney, William Pettersson, Marc Culler,
Nathan M. Dunfield, Matthias Goerner, and others 1999-present. This
code is released under the `GNU General Public License, version 2`_ or
(at your option) any later version as published by the Free Software
Foundation.

.. _Regina: https://regina-normal.github.io/
.. _Python: https://python.org
.. _PyPI: https://pypi.org
.. _main docs: https://regina-normal.github.io/#docs
.. _sageRegina: https://sageregina.unhyperbolic.org
.. _SageMath: https://sagemath.org
.. _tracker: https://github.com/3-manifolds/regina_wheels
.. _GNU General Public License, version 2: https://www.gnu.org/licenses/old-licenses/gpl-2.0.txt
