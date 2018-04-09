# test-scripts

FSSC test scripts and associated reference files for the ScienceTools/fermitools

This test suite is intended to be run in an empty directory. Output files will 
be written to the current directory.


### Instructions ###

1. First have a working version of the Fermi ScienceTools (Fermitools) environment
setup using conda. See (https://github.com/fermi-lat/ScienceTools-conda-recipe).
1. Download this repository with `git clone git@github.com:fermi-lat/test-scripts.git`.
Moving into this directory is not necessary.
1. Create an empty testing directory with `mkdir MY_TEST_DIR_NAME` and move there
with `cd MY_TEST_DIR_NAME`.
1. Run any of the python test suites with `python /PATH/TO/test-scripts/TEST_NAME.py`.
