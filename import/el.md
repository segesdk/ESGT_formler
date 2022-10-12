# El 

## Bedriftsaftryk

**El fra vedvarende energikilder**
_____________________________

$$ El_v = F \cdot OMV$$

Hvor: 

* F: Elforbrug = indtastes af bruger [kWh]
* OMV: omregningsfaktor for el fra vedvarende energikilder = 0 [kg CO2/kWh]


**El fra fossile energikilder**
_____________________________

$$ El_f = F \cdot OMF$$

Hvor:

* F: Elforbrug = indtastes af bruger [kWh]
* OMF: omregningsfaktor for el fra fossile og vedvarende energikilder = 0,151 [kg CO2/kWh]

## Produktaftryk
___________________________________________

For at finde produktaftrykket, P, er det nødvendigt at fordele det samlede elforbrug på de afgrøder/marker, der vandes. 
I MO kendes oplysningen på mark “kan vandes”, men oftest er det ikke oplyst om marken reelt _er_ vandet. Derfor kan vi i første version af produktaftrykket fordele el forbruget i marken på marker der kan vandes.

$$P_{el} = \frac{F}{\sum ha_v} \cdot ha_m$$

Hvor:

* F: Elforbrug total til vanding i kWh (indtastet af bruger). er det et krav til produktaftryk????
* ha<sub>v</sub>: Sum af hektar der kan vandes
* ha<sub>m</sub>: Antal ha pr. mark 