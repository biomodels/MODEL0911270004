# MODEL0911270004: GonzalezHeydrich1994_HPAaxisRegulation_CortisolProduction

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL0911270004.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL0911270004.git@20140916`

## Usage

Importing the model package.

`import MODEL0911270004 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**A computer simulation of the hypothalamic-pituitary-adrenal axis.**   
Gonzalez-Heydrich J, Steingard RJ, Kohane I. _Proc Annu Symp Comput Appl Med
Care_ 1994;:1010 [7949852](http://www.ncbi.nlm.nih.gov/pubmed/7949852) ,  
**Abstract:**   
This paper describes the construction of a computer model that simulates the
hypothalamic-pituitary-adrenal axis (HPA axis) regulation of cortisol
production. It is presented to illustrate the process of physiological
modeling using standard "off the shelf" technologies. The model simulates
components of the HPA axis involved in the continuous secretion and
elimination of cortisol, adrenocorticotropin (ACTH), and corticotropin
releasing hormone (CRH). The physiological relations of these component pieces
were modeled based on the current knowledge of their functioning. Rate
constants, half lives, and receptor affinities were assigned values derived
from the experimental literature. At its current level of development the
model is able to accurately simulate the timing, magnitude and decay of the
ACTH and cortisol concentration peaks resulting from the ovine-CRH stimulation
test in normal and hypercortisolemic patients. The model will be used to
predict the effects of lesions in different components of the HPA axis on the
time course of cortisol and ACTH levels. We plan to use the model to explore
the experimental conditions required to distinguish mechanisms underlying
various disorders of the HPA axis, particularly depression. Efforts are
currently underway to validate the model for a large variety of normal and
pathological perturbations of the HPA axis.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Gonzalez-Heydrich J, Steingard RJ, Kohane I.
(1994) - version02** ](http://www.cellml.org/models/gonzalezheydrich_steingard
_kohane_1994_version02)

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


