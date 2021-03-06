# BIOMD0000000371: DeVries2000_PancreaticBetaCells_InsulinSecretion

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000371.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000371.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000371 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
** Channel sharing in pancreatic beta -cells revisited: enhancement of emergent bursting by noise. **   
De Vries G, Sherman A. _J Theor Biol_2000 Dec 21;207(4):513-30
[11093836](http://www.ncbi.nlm.nih.gov/pubmed/11093836),  
**Abstract:**   
Secretion of insulin by electrically coupled populations of pancreatic beta
-cells is governed by bursting electrical activity. Isolated beta -cells,
however, exhibit atypical bursting or continuous spike activity. We study
bursting as an emergent property of the population, focussing on interactions
among the subclass of spiking cells. These are modelled by equipping the fast
subsystem with a saddle-node-loop bifurcation, which makes it monostable. Such
cells can only spike tonically or remain silent when isolated, but can be
induced to burst with weak diffusive coupling. With stronger coupling, the
cells revert to tonic spiking. We demonstrate that the addition of noise
dramatically increases, via a phenomenon like stochastic resonance, the
coupling range over which bursting is seen. Copyright 2000 Academic Press.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **De Vries G, Sherman A. (2000) - version01**
](http://www.cellml.org/models/devries_sherman_2000_version01)

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


