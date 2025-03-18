Here is the python notebook we used for the acceptance/rejection and VEGAS algorithms for the Drell-Yan Event Generator.
The code has two main sections: OVERHEAD and INFERENCE
The OVERHEAD block only needs to be run once and is almost entirely dedicated to setting up the Papaefstathiou function and VEGAS grid adaptations
The INFERENCE block is much faster, especially for VEGAS because it doesn't require as many function evaluations
No special instructions to run the notebook, the values in the 2nd block can be edited to compare the two methods.
