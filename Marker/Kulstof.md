 
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

Der er to ændringer i scenarier, som har indflydelse på mængden af kulstof i mineraljord
1. **Halmnedmulding/bjærgning** (halmnedmulding tilfører ekstra kulstof til marken hvorimod bjærgning fjerner kulstof fra marken)
1. **Efterafgrøder/mellemafgrøder** (tilfører ekstra kulstof til marken)

### **1. Halmnedmulding/bjærgning** 

Hvis en mark ændres fra "bjærgning af halm" til "halmnedmulding" i scenarie, skal Δ<sub>halm</sub> *trækkes fra* Δ<sub>jord</sub>, fordi optaget af kulstof øges og fordampningen derved sænkes

Omvendt, hvis en mark ændres fra "halmnedmulding" til "bjærgning af halm", skal Δ<sub>halm</sub> *lægges til* Δ<sub>jord</sub>, fordi optaget af kulstof sænkes og fordampningen derved øges


$$\Delta_{jord_{justeret}} = \Delta_{jord} \pm \Delta_{halm}$$ 


$$\Delta_{halm} = (K \cdot OKH) \cdot T \cdot PU $$

Hvor 


* K = Kerneudbytte. Fås fra MO på hoveafgrøden, (kg eller FEN)
* OKH = omregningsfaktor kerne til halm fås fra [regneark](https://seges.sharepoint.com/:x:/s/GreenAction/Efh8eaic0HdFuXLk2cea-f8BUvxqW-wiCgPAb7-HCUh18w?e=S5n3Y4) (fane data, kolonne R)
* T: Tørstoffraktion af høstet produkt = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!J1&action=embedview)
* PU : Puljeændring, kg CO2/kg halm-ts. Findes i https://segesinnovation.atlassian.net/browse/GT-834



### **2. Efterafgrøder/mellemafgrøder** 

Hvis en der tilføjes en efter- eller mellemafgrøde til en mark i scenarie, skal Δ<sub>efterafgrøde</sub> *trækkes fra* Δ<sub>jord</sub>, fordi optaget af kulstof øges og fordampningen derved sænkes


$$\Delta_{jord_{justeret}} = P_{MO} - P_{efterafgrøde}$$ 

hvor 
PME = puljeændringen mark med efterafgrøde i CO2 

P MO = Puljeændring (HUM+ROM)fra MO i kg CO2

P efterafgrøde = Puljeændring som følge af efterafgrøde, kg ts 

$$P_{efterafgrøde} = B \cdot PU$$

Hvor 

P efterafgrøde = Puljeændring som følge af halmnedmuldning er i kg ts

B: Total afgrøderester (biomasse), over + under jord = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Beregninger%27!L1&action=embedview)

PU : Puljeændring, kg CO2/kg efterafgrøde ts. Findes i https://segesinnovation.atlassian.net/browse/GT-896

