# A benchmark study for real-time optimal control of connected HEVs

Developing advanced control for connected hybrid electric vehicles (HEVs) has become anticipated to enhance fuel economy and mobility, while there exists a gap between the abundance of controller developments and the scarcity of bench-marking baselines. Hence, we present a benchmark study for real-time optimal control of connected HEVs, which was honored with the Gold Award for the benchmark challenge session of the IFAC Conference on Engine and Powertrain Control, Simulation and Modeling (E-CoSM) 2021. 

In this repository, we present the awarded benchmark controller. The developed benchmark controller formulates a two-layer hierarchical predictive control framework, integrating eco-velocity planning in the upper layer and a power management strategy (PMS) in the lower layer, to minimize fuel consumption while enforcing constraints and satisfying multiple traffic rules. 

The E-CoSM 2021 benchmark challenge is still an open topic, the relevant benchmark problem description and the simulator can be  provided via the
link: http://shenlab.jp/ecosm2021/program/benchmark-challenge.html.

Finally, we welcome the opportunity for focused discussions of the benchmark controller among relevant researchers.

## note
1. Initialization file
    - <font color=Red>"InitialParameter_main.m"</font>：main function
