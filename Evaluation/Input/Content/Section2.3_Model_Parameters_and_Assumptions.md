### 2.3.1	Absorption

Absorption observed in clinical studies can be fully explained by passive absorption.

### 2.3.2	Distribution

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

### 2.3.3	Metabolism, Elimination and Induction

Verapamil is metabolized by CYP3A4  and CYP2C8. 

Mechanism-based inactivation of CYP3A4  ([Rowland-Yeo 2011](# 5 References)) was taken into account.

### 2.3.4	Automated Parameter Identification

The parameter identification tool in PK-Sim has been used to estimate selected model parameters by adjusting to PK data of the clinical studies that were used in the model building process. 

The is result of the final parameter identification is shown in the table below:

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| Specific intestinal permeability | 1.6341738226E-05 | cm/min |
| Solubility at reference pH | 43514.8753161441 | mg/l |
| kinact CYP3A4 | 0.0376212371 | 1/min |
| mucosa permeability | 0.0015095540335 | cm/min |

