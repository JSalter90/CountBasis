# CountBasis

Code used in 'Emulating computer models with high-dimensional count output'

General UQ/emulation functions are taken from (and updated at) https://github.com/JSalter90/UQ

The majority of emulators were fitted with hetGP. For the homoscedastic comparison (not in main paper), extra steps are required, with functions from https://github.com/BayesExeter/ExeterUQ required, and line 6 of `uq_code/Gasp.R` needs its path editing to point to these. This is included for completeness, however is not the best approach here, and is commented out so that the main code should run without any edits.





