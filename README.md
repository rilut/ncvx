NCVX
====

NCVX is a package for modeling and solving problems with convex objectives and decision variables from a nonconvex set.
The solver methods provided and the syntax for constructing problems are discussed in [our associated paper](http://stanford.edu/~boyd/papers/ncvx.html).

NCVX is built on top of [CVXPY](http://www.cvxpy.org/),
a domain-specific language for convex optimization embedded in Python.

Installation
------------

The easiest way to install the package is to run ``pip install ncvx``.

To install the package from source, run ``python setup.py install`` in the main folder.
The package has CVXPY and munkres as dependencies.
