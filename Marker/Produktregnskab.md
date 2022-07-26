# **Produktregnskab for afgrøder**

## **Intro**
_Fagligt notat kan læses [HER](https://seges.sharepoint.com/sites/GreenAction/Delte%20dokumenter/General/Produktregnearks/skh20220215_Datagrundlag_klimaregnskab_planteprodukter.docx?web=1)_

## **Beregninger**

Når vi kender klimaftrykket på den enkelte mark, kan produktaftrykket pr ha findes ved at summere aftrykket fra marker med samme type afgrøde, og dividere med disses samlede antal hektar.

### **Eksempelberegning**

På CVR 11223344 findes tre marker med vårbyg:

* Mark 1 = 40 ha vårbyg
* Mark 2 = 180 ha vårbyg
* Mark 3 = 80 ha vårbyg

Der beregnes klimaaftryk på markerne enkeltvis, til brug i bedriftsaftrykket. Dette inkluderer beregninger for udledningskilderne:

1. [Gødning (handels- husdyr- og anden organisk)](https://github.com/segesdk/ESGT_formler/blob/main/Marker/G%C3%B8dning_og_nitrifikationsh%C3%A6mmer.md)
2. [Kalkning](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Kalkning.md)
3. [Organogene jorde](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Organogene_jorde.md)
4. [Afgrøderester](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Afgr%C3%B8derester.md)
5. [Nitratudvaskning](https://github.com/segesdk/ESGT_formler/blob/main/Marker/Nitratudvaskning.md)
6. Afgræsning (mangler afklaring/beregning)
7. Pesticider (mangler afklaring/beregning)
8. Udsæd (mangler afklaring/beregning)
9. Brændsstofforbrug (mangler afklaring/beregning)
10. Tørring og lagring (mangler afklaring/beregning)
11. Forfrugtsværdier (mangler afklaring/beregning)
12. Kulstoflagring (mangler afklaring/beregning)

### **Produktaftryk:**

Samlet udledning for marker med vårbyg, CO<sub>2</sub>eVårbyg:

$$CO_2eMark1 = CO_2eGødning + CO_2eKalkning \dots + CO_2eKulstoflagring $$
$$CO_2eMark2 = CO_2eGødning + CO_2eKalkning \dots + CO_2eKulstoflagring $$
$$CO_2eMark3 = CO_2eGødning + CO_2eKalkning \dots + CO_2eKulstoflagring $$

$$CO_2eVårbyg = CO_2eMark1 + CO_2eMark2 + CO_2eMark3 $$

Produktaftryk, P, for vårbyg:

$$P_{Vårbyg} = \frac{CO_2eVårbyg}{40+180+80}$$

Mere generelt kan produktaftrykket, P, for en afgrøde, a, formuleres som:

$$P_a = \frac{\sum_{j=1}^{m_a} \sum_{i=1}^{n_a} CO_2e_{i,j}}{A_a}$$

Hvor: 

* n<sub>a</sub> = udledningskilder inkluderet i beregningen for marken med afgrøde a
* m<sub>a</sub> = marker hvor afgrøde a dyrkes
* A<sub>a</sub> = det samlede areal hvorpå afgrøde a dyrkes







