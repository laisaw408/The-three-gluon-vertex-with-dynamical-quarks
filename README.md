# The-three-gluon-vertex-with-dynamical-quarks

This repository contains the data for the four form factors of the transversely projected three-gluon vertex, obtained from the Schwinger–Dyson equation (SDE) of this vertex within the 3PI effective-action formalism. The SDE is solved numerically in unquenched QCD with two light degenerate quark flavors, using as input the quark, gluon, and ghost propagators from lattice QCD simulations, together with the form factors of the quark–gluon and ghost–gluon vertices from Schwnger-Dyson equations.
In addition to the fully assembled form factors, the dataset also includes the individual contribution of each diagram entering the SDE to each form factor. This enables a detailed diagrammatic analysis of the three-gluon vertex in the 3PI framework.

The file G1234-Log-Unquenched.dat contains the numerical data for the four unquenched form factors, $G_i$, with $i=1,2,3,4$, already fully assembled. Each form factor is stored as a three–dimensional array of the form Gi(nxx,nxx,nth), with nxx=30 and nth=20. 

TThe files 'Gi-Diagram-Contributions.dat' contain the individual diagrammatic contributions to each form factor, $G_i$. The data layout is the same, Gi(nxx,nxx,nth), with nxx=30 and nth=20. 
The diagram labels follow the convention:

GiGluon – contribution from the gluon triangle diagram;

GiGhost – combined contribution of the two ghost-triangle diagrams;

GiQuark – combined contribution of the two quark-triangle diagrams;

GiSword – contribution from the three swordfish diagrams.
