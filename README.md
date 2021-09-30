# CFE
IDL and Fortran routines for calculating the cluster formation efficiency

# Contents

CFE_Fortran: 
The folder contains six files.
- f_cfe.f90: module containing functions for calculating the CFE as a
  function of galaxy-scale observables.
- f_cfelocal.f90: module containing functions for calculating the CFE 
  as a function of local quantities.
- parameters.in: text file containing the adjustable model parameters.
- testCFE.f90: example test program to calculate the CFE in the solar 
  neighbourhood using galaxy-scale observables as input.
- testCFElocal.f90: example test program to calculate the CFE in the solar 
  neighbourhood using local quantities as input.
- This README.
See the header of either f_cfe.f90 or f_cfelocal.f90 for a more detailed 
explanation.

CFE_IDL: 
The folder contains three files.
- f_cfe.pro: contains functions for calculating the CFE as a function of
  galaxy-scale observables.
- f_cfelocal.pro: contains functions for calculating the CFE as a function
  of local quantities.
- This README.
See the header of either f_cfe.pro or f_cfelocal.pro for a more detailed 
explanation.


# Installation

Fortran:
    The functions are provided in a module and therefore cannot be used as
    stand-alone tools. In order to function properly, the module and its
    functions need to be called from the program they are used in. Example
    programs are provided in testCFE.f90 and testCFElocal.f90 for the galaxy-
    scale and local formulations of the model, respectively. These examples are
    also shown in the headers of f_cfe.f90 and f_cfelocal.f90.

IDL: 
    The function files need to be located in the working directory, or in some
    other location specified in your IDL_PATH. They can then be called as
    detailed in the headers of f_cfe.pro and f_cfelocal.pro.


# Terms of Use

These routines are free software provided under the GNU v3.0 Public License and 
come without any warranty. If you use these routines while preparing a paper or 
talk, the author would appreciate it if you cite the paper in which the CFE 
model was presented:
    Kruijssen, J. M. D., 2012, MNRAS 426, 3008
         

# Availability

These routines and their possible future updates are available at:
    http://www.github.com/mustang-project/CFE


# Contact

The routines have been thoroughly tested, but the possibility of bugs always
exists. If you have a question, comment, or suggestion, please feel free to
contact me at:
    kruijssen[[at]]uni-heidelberg.de


Diederik Kruijssen

Garching, August 2012

(last modified September 2021)

