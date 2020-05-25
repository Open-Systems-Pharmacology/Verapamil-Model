### 2.3.1 Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2 Distribution

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3 Metabolism, Elimination and Induction

Verapamil is metabolized by CYP3A4  and CYP2C8.

The first model simulations showed that gut wall metabolism was underrepresented in the PBPK model. In order to increase gut wall metabolism, the “mucosa permeability on basolateral side” (jointly the model parameters in the mucosa: ``P (interstitial->intracellular)`` and ``P (intracellular->interstitial)``) was estimated. A decrease in this permeability may lead to higher gut wall concentrations and, in turn, to a higher gut wall elimination. This parameter was preferred over other parameters such as relative CYP3A4 expression or fraction unbound (fu) in the gut wall as it is technically not limited to a maximum value of 100%.

Mechanism-based inactivation of CYP3A4 was taken into account. The K<sub>I</sub> was implemented as reported by Rowland-Yeo et al. ([Rowland-Yeo 2011](#5-References)), the k<sub>inact</sub> was optimized ([Section 2.3.4](#Automated-Parameter-Identification))

### 2.3.4 Automated Parameter Identification

The parameter identification tool in PK-Sim has been used to estimate selected model parameters by adjusting to PK data of the clinical studies that were used in the model building process. 

The is result of the final parameter identification is shown in the table below:

| Model Parameter            | Optimized Value | Unit` |
| -------------------------- | --------------- | ---- |
| `Specific intestinal permeability` | 1.6341738226E-05 | cm/min |
| `Solubility at reference pH` | 43514.8753161441 | mg/l |
| `kinact` CYP3A4 | 0.0376212371 | 1/min |
| Basolateral mucosa permeability<br />(``P (interstitial->intracellular)``, ``P (intracellular->interstitial)``) | 0.0015095540335 | cm/min |

