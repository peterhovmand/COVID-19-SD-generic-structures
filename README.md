# Overview

This repository contains a collection of System Dynamics generic structures related modeling COVID-19 and the social impact. System Dynamics (SD) is "the use of informal maps and formal models with computer simulation to uncover and understand endogenous sources of system behavior" (Richardson, 2011, 241). With SD computer models originally implemented in the [DYNAMO](https://en.wikipedia.org/wiki/DYNAMO_(programming_language)) programming language, the focus was on removing the ingenuity of computer program with the "corrollary ... that models formulated by different users of the same situation will be quite similar and easily compared" (Pugh, 1963, p. 1). The result has been an emphasis in SD on recognizing, using, and extending generic structures. 

The goal of this respoitory is help people find and existing SD structures along with developing and sharing new SD structures related to COVID-19 that represent the best practics of SD modeling related to COVID-19 research. Specifically, the purpose of this public respository is to consolidate a set of generic structures related to COVID-19 modeling that can be used by others, critiqued and compared, and help accelerate the development of SD models related to COVID-19 prevention and response. 

Although there is a tendency to associate SD modeling with lumped parameter, aggregate models, SD modeling also includes some forms of indidividual or agent based modeling with an emphasis on understanding the endogenous or feedback dynamics of a system (Sterman, 2018). Hence, the repository includes examples of both aggregate, lumped parameter SD models and individual or agent based models. 

# Generic Structures
In SD, there have been two different views on the nature of generic structures (Paich, 1985). One view holds that generic structures are feedback mechanisms that a generalizable *within* a field, while the second view holds that generic structures are feedback mechanisms that generalize *across* fields (Paich). Lane (1998) focuses on generic structures as "dynamic feedback systems that support particular but whidely applicable behavioral insights" (p. 936) and draws a distinction between three different types of generic structures: canonical situation models, abstracted micro-structures or molecules, and counter-intuitive system archetypes. While system archetypes (e.g., Senge, 1990) have been quite popular, the emphasis in this collection is on generic structures represented as formal models that can be simulated on a computer, i.e., canonical situation models and molecules. 

The scale of these generic structures can vary greatly. For example, the suspectible-infectious-recovered or SIR model (e.g., Sterman, 2000) is a standard and relatively simple molecule used to represent a wide range of situations well beyond infectious disease dynamics. Many COVID-19 models, regardless of their implementation, build on the basic SIR model. Alternatively, one could look at a canonical situation model such as the Limits to Growth model that covers social, environmental and ecomomic sectors of the global economy. 

Determining the scale of a model *a priori* is difficult without some comparative modeling, but in order to do this, modelers must work to both share their models and compare the results. If, for example, we can capture the overall dynamics COVID-19 and implications using relatively simple and easy to understand SIR models, then we should do so. But, this type of use is only justified if we have already built, tested, and compared other models that challenge the underlying assumptions of aggregation and found the results to be insensitive to assumptions related to levels of aggregation. Hence, the collection includes generic structures at all scales. 

# How to Use

To use the structures in this respository, "fork" the reository if you want to duplcate and use the structures on our own. 

# How to Contribute

There are a number of ways to contribute, testing and critiquing to sharing code or models:

* To flag a problem with a structure, clarify something that doesn't make sense orm request a feature, create an issue under the issues tab.
* To contribut struture that may be a generic structure and you want to share/critique, upload the structure to the to the generic structures folder. 
* If you see something that is missing, create an issue.
* If you want to define a project to respond to something that is missing, create a project. 

# Contributors (alphabetical order)
[Peter S. Hovmand](https://brownschool.wustl.edu/Faculty-and-Research/Pages/Peter-Hovmand.aspx)

# References
[Lane, D. C. (1998). Can we have confidence in generic structures? *Journal of Operational Research Society, 49*, 936-947.](https://www.tandfonline.com/doi/abs/10.1057/palgrave.jors.2600605) 

[Paich, M. (1985). Generic structures. *System Dynamics Review, 1*(1), 126-132.](https://onlinelibrary.wiley.com/doi/abs/10.1002/sdr.4260010111)

Pugh, A. L. (1963). *The DYNAMO User’s Manual*. Cambridge, MA: The MIT Press.

[Richardson, G. P. (2011). Reflections on the foundations of system dynamics. *System Dynamics Review, 27*(3), 219-243.](https://onlinelibrary.wiley.com/doi/abs/10.1002/sdr.462) 

Senge, P. (1990). *The fifth discipline.* New York, NY: Curency Doubleday.

Sterman, J. D. (2000). *Business dynamics: Systems thinking and modeling for a complex world*: Irwin McGraw-Hill.

[Sterman, J. D. (2018). System dynamics at sixty: the path forward. *System Dynamics Review, 34*, 5-47.](https://onlinelibrary.wiley.com/doi/abs/10.1002/sdr.1601)

