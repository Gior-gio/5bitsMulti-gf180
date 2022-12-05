# Caravel User Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

| :exclamation: Important Note            |
|-----------------------------------------|

## 5-Bits Multiplier

Digital flow implementation using OpenLane for a custom 5-bit multiplier.

It works like the Wallace's or Dada's multiplier, using the long multiplication algorithm and uses a custom adder which works like this:

![221Adder.png](./Media/221Adder.png)

The addition tree is as follows:

![CustomMultiply.png](./Media/CustomMultiply.png)

It was presented as one of the exercises of the subject "Digital Systems II" in the first semester of 2022 at UIS, Santander, Colombia

### Final result in Klayout

![FinalResult2.png](./Media/FinalResult2.png)
