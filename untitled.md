The plan for PyChemia is to create a robust infrastructure to automatize
first principles calculations. From its conception PyChemia was created
to implement Global Searchers and execute complex atomistic simulation
tasks. That is the most functionality and will remain to put emphasis 
on that. However, PyChemia has been growing in some other directions as 
well. This document is a **roadmap** of the kind of developments that we
are expecting to be done in the forthcoming months for the code.

ToDo List
=========

## Development

   * Double support Python >= 2.7 and >= 3.3
   * Travis Continous Integration
   * Coverage and links with coverallis.io
   * Increasing the coverage (Currently 26%)
   * Reducing dependencies (numpy, scipy, future)
   * Flexible load of modules according with libraries found
   * Support for SPGLIB >= 1.9.0
   * New API documentation of Sphinx
   * Code uploaded to PIPY   
   * Exposure on Google search

Science
------

   * Magnetic Moments (VASP)
   * Orbital Populations (ABINIT)
   * New VASP minimizer
   * New ABINIT minimizer
   * Searchers, modules, classes and subclasses
   * Moving to unicode, Py3 and Mongo
   * Internal PyChemiaMasterDB

Communication
-------------

   * New documentation structures
     Wiki and Github pages for PyChemia
   * Internal wiki for group (development and research)
   * New Jupyter notebooks for tutorials (Old IPython Notebooks)
 

Tasks
=====

   * Adam: We will work on applications of global search on three different contexts, traditional geometry optimization, magnetic moment optimization, and orbital occupation for strongly correlated materials.
