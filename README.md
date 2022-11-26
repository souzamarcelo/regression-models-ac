# Improved Regression Models for Algorithm Configuration

This repository contains a set of auxiliary functions to apply regression models in the context of algorithm configuration.

The configuration scenarios can be found [here](https://github.com/souzamarcelo/ac-scenarios).

The following ``target runner`` scripts implement the linear regression models:
+ [BSFS](scripts/bsfs.py/)
+ [HHTA](scripts/hhta.py/)
+ [ILSBQP](scripts/ilsbqp.py/)
+ [TSCPP](scripts/tscpp.py/)

Nonlinear models:
+ [BSFS - piecewise linear (2 pieces)](scripts/target-runner-bsfs-piecewise2.py)
+ [BSFS - piecewise linear](3 pieces)](scripts/target-runner-bsfs-piecewise3.py)
+ [BSFS - loglog linear](scripts/target-runner-bsfs-logloglin.py)
