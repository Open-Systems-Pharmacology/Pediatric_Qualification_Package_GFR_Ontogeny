The presented qualification report evaluates the predictive performance of the OSP suite to predict glomerular filtration rate (GFR)-mediated drug clearance in children.

Therefore, PBPK models of specific *in vivo* probe substances covering children aged below 6 months up to adolescents were built and evaluated. All models are whole-body PBPK models, allowing for dynamic pediatric translation in all organs. The qualification report demonstrates the level of confidence of the OSP suite with regard to reliable PBPK predictions of age related GFR-mediated drug clearance during model-informed drug development. The presented PBPK models as well as the respective qualification plan and qualification report are provided open-source and transparently documented (https://github.com/Open-Systems-Pharmacology/Pediatric-Qualification-Package-GFR). 


## Translation of Adult PBPK to Children

Using a developed and validated (adult) PBPK model for an *in vivo* probe substance, a pediatric PBPK model can be established for children by translating physiology, clearance processes (as parameterized in the adult model) and age-dependent protein binding including the variability therein.[[1](#reference)]

The PBPK models are developed with clinical data of healthy adult subjects obtained from the literature. Plasma concentrations following multiple-dose application, mass balance information and other clinical measurements need to be included for model development, if available. During model translation from adults to children for a specific substance, uncertainties in data-quality caused by impact of disease or the target study population, inaccurate in vitro assay-techniques regarding mass balance, as well as study differences may cause not being able to adequately predict the PK in children for all reported studies. 

Prediction performance of the PBPK model for these probe substances in children are then shown by means of e.g. predicted versus observed clearance-ratio plots, of which the results support an adequate prediction of the ontogeny function for the application of PBPK model translation of adult PBPK to children.

For qualification purpose, during the translation of adult PBPK to children the following assumptions and considerations were made: 

- when translating an adult model to children, it was assumed that the metabolism and excretion pathways are qualitatively the same in children as in adults.
- no further changes to input parameters other than those for the physiology and protein binding. All other parameters (e.g. lipophilicity) were kept unchanged. 

## Anthropometric and Physiological Information 

Regarding the age-dependencies of the relevant anthropometric (height, weight) and physiological parameters (e.g. blood flows, organ volumes, binding protein concentrations, hematocrit, cardiac output) in children was gathered from the literature and has been previously published [[2](#reference)]. The information was incorporated into PK-Sim® and was used as default values for the simulations in children.

The  applied ontogeny and variability of plasma proteins that are integrated into PK-Sim® for translation to children are described in the publicly available ‘PK-Sim® Ontogeny Database Version 7.3' [[3](#reference)] or otherwise referenced for the specific process.

### Qualification of **GFR ontogeny**

For the qualification of the GFR elimination of compounds, the following probe substances was included:

- Amikacin [[4](#reference)]
- Vancomycin [[5](#reference)]

### References

[1] [Maharaj AR, Barrett JS, Edginton AN. A workflow example of PBPK modeling to support pediatric research and development: case study with lorazepam. The AAPS journal. 2013;15(2): 455-464.](https://www.ncbi.nlm.nih.gov/pubmed/23344790)

[2] [Edginton AN, Schmitt W, Willmann S. Development and evaluation of a generic physiologically based pharmacokinetic model for children. Clin Pharmacokinet. 2006;45(10):1013-34.](https://www.ncbi.nlm.nih.gov/pubmed/16984214)

[3]  [OSPSuite.Documentation/PK-Sim Ontogeny Database Version 7.3.pdf ](https://github.com/Open-Systems-Pharmacology/OSPSuite.Documentation/blob/38cf71b384cfc25cfa0ce4d2f3addfd32757e13b/PK-Sim%20Ontogeny%20Database%20Version%207.3.pdf)

[4] [Amikacin-Model, Whole-body PBPK model of Amikacin. https://github.com/Open-Systems-Pharmacology/Amikacin-Model](https://github.com/incei/Amikacin-Model)

[5] [Vancomycin-Model, Whole-body PBPK model of Vancomycin. https://github.com/Open-Systems-Pharmacology/Amikacin-Model](https://github.com/incei/Vancomycin-Model)