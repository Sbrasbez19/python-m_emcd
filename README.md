<H1> Python implementation of the M-EMCD algorithm</H1>

The memcd.ipynb file contains an implementation of the M-EMCD algorithm presented in https://doi.org/10.1007/s10618-017-0528-8. Before execution, install the libraries in the file requirements.txt. 
All the code was developed and tested using Python 3.13.7.

The memcd.ipynb notebook contains a series of functions organized as follows:
  - UTILS: a number of utility functions needed to run the algorithm. These are basically needed to generate the MultiGraph in the correct way so that the algorithm can work.
    If working with a pre-existing networkx MultiGraph be sure the graph contains a 'layers' attribute and that the keys of your edges correspond to the specified layers

  - M-EMCD: all the functions needed for the correct usage of the algorithm.
  - TAGARELLI NETWORK: a function generating the network and initial clustering presented in the paper, in particular the network in Figure 4.
    
Just execute everything in order, the final cells contain an exemple of execution on the provided network.
