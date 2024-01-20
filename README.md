# Preference_Driven_MPC_Tuning

This repository contains the source code for my Master's thesis, focusing on Model Predictive Control (MPC) tuning. 

The implementation builds upon the foundational code of GLIS available at [GLIS website](http://cse.lab.imtlucca.it/~bemporad/glis/) and leverages examples from MATLAB's [Model Predictive Control Toolbox](https://www.mathworks.com/products/model-predictive-control.html).

For optimization using the preference-driven GLIS approach, the script [`glisp.m`](/glisp.m) is executed.

To perform optimization with the standard GLIS method, [`glis.m`](/glis.m) is utilized, primarily for benchmarking against the preference-based variant.

The algorithm initialization is handled by [`glis_init.m`](/glis_init.m).

The three directories - [`CSTR`](/CSTR), [`LKOA`](/LKOA), and [`PenCart`](/PenCart) - contain the scenario-specific simulation code. They cover obstacle avoidance and lane keeping in autonomous driving, state switching for a continuous stirred tank reactor (CSTR), and controlling an inverted pendulum on a cart system, respectively.
