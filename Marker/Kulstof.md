 
# **Kulstof i mineraljord**
## **Bedriftsaftryk**

Kulstofændringen, Δ<sub>jord</sub> [kg CO<sub>2</sub>e], i mineraljord beregnes pr mark og summeres herefter for alle marker på bedriften.

 $$\Delta_{jord} = C_{HUM} + C_{ROM} \cdot \frac{44}{12} $$

Hvor:

* C<sub>HUM</sub>: Ændringen i mængden af kulstof i HUM puljen fra april til april = kommer fra MO
* C<sub>ROM</sub>: Ændringen i mængden af kulstof i ROM puljen fra april til april = kommer fra MO

___
## **Produktaftryk**

Kulstof i mineraljord indgår *ikke* i produktaftryk på nuværende tidspunkt

___
## **Scenarier**

Fagligt notat kan læses [HER](https://seges.sharepoint.com/:w:/s/GreenAction/EWTMZzrGtuhIhp7uoODwSH0Bv_UJ6mpXR6SZs1zfBktwbQ?e=oVgofk)

Der er to ændringer i scenarier, som medfører en korrigering af Δ<sub>jord</sub>:

1. **Halmnedmulding/bjærgning** (halmnedmulding tilfører ekstra kulstof til marken hvorimod bjærgning fjerner kulstof fra marken)
1. **Efterafgrøder/mellemafgrøder** (tilfører ekstra kulstof til marken)

### **1. Halmnedmulding/bjærgning** 

Hvis en mark ændres fra "bjærgning af halm" til "halmnedmulding" i scenarie, skal Δ<sub>halm</sub> *trækkes fra* Δ<sub>jord</sub>, fordi optaget af kulstof øges og CO<sub>2</sub>-fordampningen derved sænkes

Omvendt, hvis en mark ændres fra "halmnedmulding" til "bjærgning af halm", skal Δ<sub>halm</sub> *lægges til* Δ<sub>jord</sub>, fordi optaget af kulstof sænkes og CO<sub>2</sub>-fordampningen derved øges

$$\Delta_{jord_{korrigeret}} = \Delta_{jord} \pm \Delta_{halm}$$ 


$$\Delta_{halm} = H_u \cdot T \cdot P_{halm} $$


Hvor 

* H<sub>u</sub>: Halmudbytte = For frøgresser aflæses en [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!S1&action=embedview) fra regnearket. For øvrige afgrøer beregnes halmudbyttet:

$$H_u = U \cdot H_f$$

Hvor

* U: Udbytte = Læses fra MO [kg _eller_ FE]
* H<sub>f</sub>: Halmfraktion ift. udbytte = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!R1&action=embedview) [ts]
* T: Tørstoffraktion af høstet produkt = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!J1&action=embedview)
* P<sub>halm</sub>: Puljeændring, kg CO2/kg halm-ts = Aflæses af Tabel 1

| Jordtype  | Lerprocent, % | Puljeændring, kg CO2/kg halm-ts  |
| --------- | ---------- | ------------- |
| JB1 + JB2 | 3 pct.     | 0,1928 kg CO2 |
| JB3 + JB4 | 8 pct.     | 0,2174 kg CO2 |
| JB5-JB10  | 12 pct.    | 0,2325 kg CO2 |

*Tabel 1: Puljeændring som følge af halmnedmulding. Hvis vi i første omgang ikke vil gøre korrektionen afhængig af jordtypen, så anvender vi korrektionsværdierne for JB3 + JB4.*

### **2. Efterafgrøder/mellemafgrøder** 

Hvis en der tilføjes en efter- eller mellemafgrøde til en mark i scenarie, skal Δ<sub>efterafgrøde</sub> *trækkes fra* Δ<sub>jord</sub>, fordi optaget af kulstof øges og CO<sub>2</sub>-fordampningen derved sænkes

$$\Delta_{jord_{korrigeret}} = \Delta_{jord} - Δ_{afgrøde}$$ 


$$Δ_{afgrøde} = B \cdot P_{afgrøde}$$

Hvor 

* B: Total afgrøderester (biomasse), over + under jord = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Beregninger%27!L1&action=embedview)
* P<sub>afgrøde</sub>: Puljeændring, kg CO2/kg efterafgrøde ts. = Aflæses af Tabel 2

| Jordtype  | Lerprocent, % | Puljeændring, kg CO2/kg efterafgrøde-ts  |
| --------- | ---------- | ------------- |
| JB1 + JB2 | 3 pct.     | 0,1388 kg CO2 |
| JB3 + JB4 | 8 pct.     | 0,1561 kg CO2 |
| JB5-JB10  | 12 pct.    | 0,1678 kg CO2 |

*Tabel 2: Puljeændring som følge af tilføjelse af efter- eller mellemafgrøde. Hvis vi i første omgang ikke vil gøre korrektionen afhængig af jordtypen, så anvender vi korrektionsværdierne for JB3 + JB4.*




