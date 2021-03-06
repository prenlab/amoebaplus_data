# AMOEBA+ database

## valence2021
* tinker.key: final valence parameters for the organic molecules
* xyz: organic molecules in tinker xyz format

## chargeflux

## polarizability
* `CCSD_POLAR.XYZ`: CCSD molecular polarizability for 7211 molecules, taken from QM7b database [1]
* `EXPT_POLAR.XYZ`: Experimental molecular polarizability for 422 molecules, taken from [2]. The molecular geometry was optimized at MP2/6-31G\* level of theory.
* `MP2_POLAR.XYZ`: MP2 molecular polarizability for 73 neutral molecules. Geometry at MP2/6-31G\* and molecular polarizability at aug-cc-pvtz level of theory, respectively.
* `MP2_POLAR_CHARGED.XYZ`: MP2 molecular polarizability for 70 charged molecules. Geometry at MP2/6-31G\* and molecular polarizability at aug-cc-pvtz level of theory, respectively.

## nonbonded
* High-level QM data
* Experimental data

## References
1. Wilkins, D. M.; Grisafi, A.; Yang, Y.; Lao, K. U.; DiStasio, R. A.; Ceriotti, M., Accurate molecular polarizabilities with coupled cluster theory and machine learning. Proceedings of the National Academy of Sciences 2019, 116 (9), 3401-3406.
1. Bosque, R.; Sales, J., Polarizabilities of Solvents from the Chemical Composition. Journal of Chemical Information and Computer Sciences 2002, 42 (5), 1154-1163
