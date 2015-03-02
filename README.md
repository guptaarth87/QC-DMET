QC-DMET: a python implementation of density matrix embedding theory for ab initio quantum chemistry
===================================================================================================

Copyright (C) 2015 Sebastian Wouters <sebastianwouters@gmail.com>

This program is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program; if not, write to the Free Software Foundation, Inc.,
51 Franklin Street, Fifth Floor, Boston, MA 02110-1301 USA.


Building and testing
--------------------

QC-DMET requires python, numpy, scipy,
[libchemps2](https://github.com/SebWouters/CheMPS2), 
[libcint](https://github.com/sunqm/libcint), and 
[pyscf](https://github.com/sunqm/pyscf).

The path to PyCheMPS2.so can be adjusted in [solver.py](src/solver.py) and
the path to the folder in which pyscf is installed in 
[localintegrals.py](src/localintegrals.py).

Start from the files test*.py.

