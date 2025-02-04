### Absorption

Verapamil is transported by P-gp. The model includes non-stereospecific P-gp transport. 

### Distribution

After testing the available organ-plasma partition coefficient and cell permeability calculation methods built in PK-Sim, observed clinical data was best described by choosing the partition coefficient calculation by `Rodgers and Rowland` and cellular permeability calculation by `PK-Sim Standard`. 

### Metabolism, Elimination and Inhibition

Verapamil is metabolized by CYP3A4 and transported by P-gp. The model includes enantioselective metabolism by CYP3A4, non-stereospecific P-gp transport. Additionally passive glomerular filtration was integrated. 

Mechanism-based inactivation of CYP3A4 and non-competitive inhibition of P-gp by all four entities (S-verapamil, R-verapamil, S-norverapamil and R-norverapamil) was taken into account. The CYP3A4 MBI KI and kinact values were taken from literature, the KI values for P-gp inhibition were optimized.


### Automated Parameter Identification

The parameter identification tool in PK-Sim has been used to estimate selected model parameters by adjusting to PK data of the clinical studies that were used in the model building process. 

The result of the final parameter identification is shown in the tables below:


#### R-verapamil

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| logP            		|  2.84  	||
| CYP3A4 kcat -> Norvera        |  34.94 	|1/min|
| CYP3A4 kcat -> D617           |  43.98	|1/min|
| P-gp kcat            		|  12.60	|1/min|
| Pgp non-competitive Ki        |  0.038	|µmol/L|
| Cellular permeability         |  9.94E-02	|cm/min|
| Intestinal permeability       |  3.54E-06	|cm/min|
| SR tablet Weibull time        |  155.24	|min|
| SR tablet Weibull shape       |  2.37		| |


#### S-verapamil

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| logP            		|  2.84  	||
| CYP3A4 kcat -> Norvera        |  26.17 	|1/min|
| CYP3A4 kcat -> D617           |  56.42	|1/min|
| P-gp kcat            		|  12.60	|1/min|
| Pgp non-competitive Ki        |  0.038	|µmol/L|
| Cellular permeability         |  9.94E-02	|cm/min|
| Intestinal permeability       |  3.54E-06	|cm/min|
| SR tablet Weibull time        |  155.24	|min|
| SR tablet Weibull shape       |  2.37		| |


#### R-norverapamil

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| logP            		|  2.84  	||
| CYP3A4 kcat -> D620           |  145.64	|1/min|
| P-gp kcat            		|  3.39		|1/min|
| Pgp non-competitive Ki        |  0.038	|µmol/L|
| Cellular permeability         |  9.94E-02	|cm/min|
| Intestinal permeability       |  3.54E-06	|cm/min|



#### S-norverapamil

| Model Parameter            | Optimized Value | Unit |
| -------------------------- | --------------- | ---- |
| logP            		|  2.84  	||
| CYP3A4 kcat -> D620           |  41.10	|1/min|
| P-gp kcat            		|  3.39		|1/min|
| Pgp non-competitive Ki        |  0.038	|µmol/L|
| Cellular permeability         |  9.94E-02	|cm/min|
| Intestinal permeability       |  3.54E-06	|cm/min|


