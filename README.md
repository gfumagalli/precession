precession
==========

**Author** Davide Gerosa

**email** d.gerosa@damtp.cam.ac.uk

**Copyright** Copyright (C) 2016 Davide Gerosa

**Licence** CC BY 4.0

**Version** 0.9.0


# DYNAMICS OF SPINNING BLACK-HOLE BINARIES WITH PYTHON

`precession` is an open-source Python module to study the dynamics of precessing
black-hole binaries in the post-Newtonian regime.  The code provides a
comprehensive toolbox to (i) study the evolution of the black-hole spins  along
their precession cycles, (ii) perform gravitational-wave driven binary inspirals
using both orbit-averaged and precession-averaged integrations, and (iii)
predict the properties of the merger remnant through fitting formulae obtained
from numerical relativity simulations. `precession` is a ready-to-use tool to 
add  the black-hole spin dynamics to larger-scale numerical studies such as 
gravitational-wave parameter estimation codes, population synthesis models to
predict gravitational-wave event rates, galaxy merger trees and  cosmological
simulations of structure formation. `precession` provides fast and reliable
integration methods to propagate statistical samples of black-hole binaries
from/to large separations where they form to/from small separations where they 
become detectable, thus linking gravitational-wave observations of spinning
black-hole binaries to their astrophysical formation history. The code is also a
useful tool to compute initial parameters for numerical relativity simulations
targeting specific precessing systems.

This code is released to the community under the [Creative Commons Attribution
International license](http://creativecommons.org/licenses/by/4.0).
Essentially, you may use `precession` as you like but must make reference to
our work. When using `precession` in any published work, please cite the paper
describing its implementation:

- *Precession. Dynamics of spinning black-hole binaries with Python.* 
Davide Gerosa, Michael Kesden. arXiv:...

`precession` is an open-source code distributed under git version-control system on

- [github.com/dgerosa/precession](https://github.com/dgerosa/precession)

API documentation can be generated automatically in html format from the code
docstrings using `pdoc`, and is uplodad to a dedicated branch of the git
repository      

- [dgerosa.github.io/precession](https://dgerosa.github.io/precession)

Further information and scientific results on the results are available at:

- [www.damtp.cam.ac.uk/user/dg438/precession](http://www.damtp.cam.ac.uk/user/dg438/precession) 
- [www.davidegerosa.com/precession](http://www.davidegerosa.com/precession)


### INSTALLATION
 
`precession` works in python 2.x and has been tested on 2.7.10. It can be
installed through [pip](https://pypi.python.org/pypi/precession):

    pip install precession

Prerequisites are `numpy`, `scipy` and `parmap`, which can be all installed
through pip. Information on all code functions are available through Pyhton's
built-in help system

    import precession
    help(precession.function)

Several tests and tutorial are available in the submodule `precession.test`. A
detailed descriptions of the functionalies of the code is provided in the
scientific paper [arXiv:num](arXiv:num) where examples are also presented. 


### CREDITS
The code is developed and maintained by [Davide Gerosa](www.davidegerosa.com). 
Please, report bugs to

    d.gerosa@damtp.cam.ac.uk

I'm happy to help you out! 

**Thanks**: E. Berti, M. Kesden, U. Sperhake, R. O'Shaughnessy, D.
Trifiro', A. Klein, J. Vosmera and X. Zhao.