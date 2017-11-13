This release fixes a bug in the out-of-bag predictions.

## Test environments

* Ubuntu 12.04 (on travis-ci), R-3.1, R-3.2, R-oldrel, R-release, R-devel
* Windows Server 2012 R2 (x64) (on AppVeyor-ci), R 3.4.2
* Rhub
  * Windows Server 2008 R2 SP1, R-devel, 32/64 bit
  * Debian Linux, R-devel, GCC ASAN/UBSAN
  * Fedora Linux, R-devel, clang, gfortran
  * Ubuntu Linux 16.04 LTS, R-release, GCC


## R CMD check results

0 ERRORs | 0 WARNINGs | 2 NOTES.

* New maintainer

This was agreed with the previous maintainer and author of the package Nicolai Meinshausen. 

* It is good practice to register native routines and to disable symbol
search.

This error seems to be recurrent but not important.

