# **El**

## **Bedriftsaftryk (mark, fjerkræ)**

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
* OMF: omregningsfaktor for el fra fossile og vedvarende energikilder = 0,136 [kg CO2/kWh] 

## **Produktaftryk (mark)**
___________________________________________
**Vanding**

For at finde produktaftrykket, P, er det nødvendigt at fordele det samlede elforbrug fra vanding på de afgrøder/marker, der vandes. 
I MO kendes oplysningen på mark “kan vandes”, men oftest er det ikke oplyst om marken reelt _er_ vandet. Derfor kan vi i første version af produktaftrykket fordele el forbruget i marken på marker der kan vandes.

$$P_{a, el} = \frac{F_v}{\sum ha_v} \cdot ha_a$$

Hvor:

* F<sub>v</sub>: Elforbrug total til vanding i kWh (indtastet af bruger). 
* ha<sub>v</sub>: Sum af hektar, der kan vandes
* ha<sub>a</sub>: Antal ha pr. mark 

**Andet el (tørring mv.)**

For at finde produktaftrykket, P, er det nødvendigt at fordele elforbruget, der ikke bruges til vanding, på de afgrøder/marker, der har afgrøder til modenhed (tørring m.v.)
I regnearket findes en kolonne hvor ja betyder at afgrøden høstet til modenhed.

$$P_{b, el} = \frac{F_t}{\sum ha_m} \cdot ha_a$$

Hvor:

* F<sub>t</sub>: Elforbrug total til tørring mv. i kWh (indtastet af bruger). 
* ha<sub>m</sub>: Sum af hektar, der har afgrøder, der høstet til modenhed
* ha<sub>a</sub>: Antal ha pr. mark 

## **Produktaftryk (Fjerkræ)**