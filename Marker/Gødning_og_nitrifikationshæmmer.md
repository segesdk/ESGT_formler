# **Gødning på marken**

## **Gødning**

### **Beregning af N<sub>2</sub>O fra handelsgødning, husdyrgødning og anden organisk gødning** 

$$N_2O_{gødning} = N_2O_{jord}  + N_2O_{NH_3}  + N_2O_{NOx}$$

Hvor:

$$N_2O_{jord} = N_{total} \cdot EF_{N_2O} \cdot \frac{44}{28}$$

$$N_2O_{NH_3} = N_{total} \cdot EF_{NH_3} \cdot  EF_{N_2O}\cdot \frac{44}{28}$$

$$N_2O_{NOx} = \frac{N_{total} \cdot EF_{NOx}}{\frac{46}{14}} \cdot EF_{N_2O} \cdot \frac{44}{28}$$

Og:
* N<sub>total</sub> = fra MDB, kg N i gødningstypen pr. mark (summering af N i gødningstypen for alle handlingerne på marken) [kg]
* EF<sub>N<sub>2</sub>O</sub> = 0,01
* EF<sub>NH<sub>3</sub></sub> = 0,05 for handelsgødning og 0,08 for husdyrgødning/anden org gødning
* EF<sub>NOx</sub> = 0,04

### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_2O_{gødning} \cdot \theta_{N_2O-CO_2}$$
Hvor: 

 * $\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub>: Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub> = 298

## **Nitrifikationshæmmer**

Ved brug af nitrifikationshæmmer sænkes aftrykket fra gødningen i jorden med 40%. N<sub>2</sub>O<sub>jord</sub> i beregningen ovenfor genberegnes derfor som:

$$N_2O_{jord} = N_2O_{jord} - (N_{nitri} \cdot EF_{N_2O} \cdot \frac{44}{28} \cdot 0,4)$$

Hvor: 

 * N<sub>nitri</sub>: Mængden af handels-, husdyr- eller anden organisk gødning som er tilsat nitrifikationshæmmere = brugerinput [kg]

_OBS: N<sub>2</sub>O<sub>NH<sub>3</sub></sub> og N<sub>2</sub>O<sub>NOx</sub> genberegnes ikke ved tilsætning af nitrifikationshæmmer_