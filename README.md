# MODEL1201140003: Lenbury2001_InsulinKineticsModel_B

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1201140003.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1201140003.git@20140916`

## Usage

Importing the model package.

`import MODEL1201140003 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Modeling insulin kinetics: responses to a single oral glucose administration or ambulatory-fed conditions.**   
Lenbury Y, Ruktamatakul S, Amornsamarnkul S. _Biosystems._ 2001
Jan;59(1):15-25. [11226623](http://www.ncbi.nlm.nih.gov/pubmed/11226623) ,  
**Abstract:**   
This paper presents a nonlinear mathematical model of the glucose-insulin
feedback system, which has been extended to incorporate the beta-cells'
function on maintaining and regulating plasma insulin level in man. Initially,
a gastrointestinal absorption term for glucose is utilized to effect the
glucose absorption by the intestine and the subsequent release of glucose into
the bloodstream, taking place at a given initial rate and falling off
exponentially with time. An analysis of the model is carried out by the
singular perturbation technique in order to derive boundary conditions on the
system parameters which identify, in particular, the existence of limit cycles
in our model system consistent with the oscillatory patterns often observed in
clinical data. We then utilize a sinusoidal term to incorporate the temporal
absorption of glucose in order to study the responses in the patients under
ambulatory-fed conditions. A numerical investigation is carried out in this
case to construct a bifurcation diagram to identify the ranges of parametric
values for which chaotic behavior can be expected, leading to interesting
biological interpretations.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **lenbury_ruktamatakul_amornsamarnkul_2001_B** ](htt
p://models.cellml.org/exposure/16d5ee315f43ef508ecfa79759f6086a/lenbury_ruktam
atakul_amornsamarnkul_2001_b.cellml/view)  
The original CellML model was created by:  
**Catherine Lloyd**   
c.lloyd@aukland.ac.nz  
The University of Auckland  
The Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


