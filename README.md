# QG-sphSymm-ancillary
Ancillary files for arXiv publication 2104.04010

depedencies:
Mathematica 12
xAct package (http://www.xact.es/) as of 2020

The main file reduction.nb can be executed from top to bottom (without executing initialization cells).

Some parts of it take considerable amount of computation time.
Hence, intermediate results are stored as mathematica dump (.mx) files. These can alternatively be re-imported at intermediate stages in reduction.nb.

The final 1st-order in time system is exported in c-form.

