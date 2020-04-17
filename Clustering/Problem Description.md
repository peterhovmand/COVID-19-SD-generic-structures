# Problem Description

Early phases of an outbreak are characterized by clusters of infections in which there is rapid spread within the cluster, but more restrained spread to the population at large. Because the aggregate models treat the entire population as interacting, they will overstate growth in the early phases (or during containment). 

# Approach
One approach to handling clustering is to treat early contact as occuring at a lower rate.

This Stella model includes explicit clustering and an approximation. The explicit clustering is done using arrays as clusters with an in-cluster contact rate and an out-of-cluster contact rate.

In the approximation, the early part of the infection has a multiplier that decrease contacts, until the cutoff is reached at which point the standard SIR formulation of contacts is used. That model is contained in the module, and is compared to the clustered model so show the similarity of behavior.

Note - the clustering effect has been optimized in this model to make the two behave as similarly as possible using the original global contact rate. Different assumptions around contact rates and intervention times will have an impact on the clustering parameters.

# Contributor 
Bob Eberlein

# License
Provided under the Creative Commons Attribution License (CC BY)
https://creativecommons.org/licenses/by/4.0
