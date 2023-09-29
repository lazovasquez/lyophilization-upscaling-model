FEniCS on Anaconda
To use our prebuilt Anaconda Python packages (Linux and Mac only), first install Anaconda, then run following commands in your terminal:

conda create -n fenicsproject -c conda-forge fenics
source activate fenicsproject

# To activate this environment, use
#
#     $ conda activate fenicsproject
#                     
# To deactivate an active environment, use
#
#     $ conda deactivate

For further information on using Anaconda, see the documentation.

Warning: FEniCS Anaconda recipes are maintained by the community and distributed binary packages do not have a full feature set yet, especially regarding sparse direct solvers and input/output facilities.

Update. 2017.2.0 release on conda-forge features MUMPS direct solver, but lacks SuperLU_dist and MPI-enabled HDF5.

https://fenicsproject.org/download/archive/

https://jsdokken.com/dolfinx-tutorial/chapter2/ns_code1.html


LATEST DEMOS
https://fenicsproject.org/olddocs/dolfin/latest/

1     python -m pip install numpy
2     python -m pip install scipy
3     python -m pip install matplotlib
