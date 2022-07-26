# **Produktregnskab for afgrøder**

## **Intro**
_Fagligt notat kan læses [HER](https://seges.sharepoint.com/sites/GreenAction/Delte%20dokumenter/General/Produktregnearks/skh20220215_Datagrundlag_klimaregnskab_planteprodukter.docx?web=1)_

## **Beregninger**

Når vi kender klimaftrykket på den enkelte mark, kan produktaftrykket pr ha findes ved at summere aftrykket fra marker med samme type afgrøde, og dividere med disses samlede antal hektar.

### **Eksempel for bedrift med vårbyg og raps**

På CVR 11223344 findes fem marker - tre med vårbyg og to med raps:

* Mark 1 = 40 ha vårbyg
* Mark 2 = 180 ha vårbyg
* Mark 3 = 80 ha vårbyg
* Mark 4 = 35 ha raps
* Mark 5 = 55 ha raps

Der beregnes klimaaftryk på markerne enkeltvis, til brug i bedriftsaftrykket. Dette inkluderer beregninger for:

* [Gødning (handels- husdyr- og anden organisk)](https://github.com/segesdk/ESGT_formler/blob/main/Marker/G%C3%B8dning_og_nitrifikationsh%C3%A6mmer.md)
* [Kalkning](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Kalkning.md) (se note nedenfor om kalkning)
* [Organogene jorde](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Organogene_jorde.md)
* [Afgrøderester](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Afgr%C3%B8derester.md)
* [Nitratudvaskning](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Nitratudvaskning.md)
* Afgræsning (mangler afklaring/beregning)
* Pesticider (mangler afklaring/beregning)
* Udsæd (mangler afklaring/beregning)
* Brændsstofforbrug (mangler afklaring/beregning)
* Tørring og lagring (mangler afklaring/beregning)
* Forfrugtsværdier (mangler afklaring/beregning)
* Kulstoflagring (mangler afklaring/beregning)

#### **Særligt for kalkning**

Vi kan endnu ikke kan fastlægge, hvilke marker, der modtager kalk, og derfor spredes det samlede CO2-bidrag fra kalk ligeligt ud på alle CVR nummerets marker. I dette eksempel vil kalk-bidraget for hhv vårbyg og raps derfor blive:

$$CO_{2kalk} = \frac{(40+180+80+35+55) \cdot 170}{100,09}\cdot 12,01 \cdot \frac{44}{12} = 29.912,01$$

$$CO_{2kalk}Vårbyg = \frac{29.912,01}{(40+180+80)} = 99,73$$

$$CO_{2kalk}Raps = \frac{29.912,01}{(35+55)} = 299,18$$






