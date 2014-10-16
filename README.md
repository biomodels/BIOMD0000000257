# BIOMD0000000257: Piedrafita2010_MR_System

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000257.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000257.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000257 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This is the self maintaining metabolism model described in the article:  
** A Simple Self-Maintaining Metabolic System: Robustness, Autocatalysis, Bistability. **   
Piedrafita G, Montero F, Morán F, Cárdenas ML, Cornish-Bowden A, _PLoS
Computational Biology_ 2010, 6(8):e1000872. doi:[10.1371/journal.pcbi.1000872]
(http://dx.doi.org/10.1371/journal.pcbi.1000872)  
**Abstract:**   
A living organism must not only organize itself from within; it must also
maintain its organization in the face of changes in its environment and
degradation of its components. We show here that a simple (M,R)-system
consisting of three interlocking catalytic cycles, with every catalyst
produced by the system itself, can both establish a non-trivial steady state
and maintain this despite continuous loss of the catalysts by irreversible
degradation. As long as at least one catalyst is present at a sufficient
concentration in the initial state, the others can be produced and maintained.
The system shows bistability, because if the amount of catalyst in the initial
state is insufficient to reach the non-trivial steady state the system
collapses to a trivial steady state in which all fluxes are zero. It is also
robust, because if one catalyst is catastrophically lost when the system is in
steady state it can recreate the same state. There are three elementary flux
modes, but none of them is an enzyme-maintaining mode, the entire network
being necessary to maintain the two catalysts

As this is a theoretical model and no units are given in the article, the
standard units (mol, seconds and litre) are used for the parameters. k8 and
k11 are set equal to k4.

Originally created by libAntimony v1.4 (using libSBML 3.4.1)


