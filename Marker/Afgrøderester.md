# **Afgrøderester på marken**

_NB Der er fire variable, som har indvirkning på beregningen af afgrøderester. Disse er:_

* _X1: Halmnedmulding, ja/nej_
* _X2: Halm er hentet som direkte input, ja/nej_
* _X3: Udbytte + halmudbytte anvendes til beregning af afgrøderest, ja/nej_
* _X4: Udbytte nedmuldnes, ja/nej_


_Fagligt notat kan læses [HER](https://seges.sharepoint.com/sites/GreenAction/Delte%20dokumenter/General/Mark/majh20220718_afgr%C3%B8derester_esgreen%20tool_input%20parametre%20og%20variabler.docx?web=1)_

### **Beregning af N fra afgrøderester på marken** 

$$N_{afgrøderester} = \frac{N_{A_{over}} + N_{A_{under}}}{O} \cdot H$$

Hvor:

* N<sub>A<sub>over</sub></sub>: N i afgrøderester over jorden [kg N/kg ts]
* N<sub>A<sub>under</sub></sub>: N i afgrøderester under jorden [kg N/kg ts]
* O: Omlægningsfrekvens
* H: Antal ha på marken

### **Beregning af N i afgrøderester over jorden, N<sub>A<sub>over</sub></sub>, afhænger af afgrødetypen**

>Hvis X1 = 1

$$N_{A_{over}} = A_{over} \cdot N_{over} $$

>Hvis X1 = 0 _og_ X2 = 0

$$N_{A_{over}} = (A_{over} - H_f \cdot U \cdot T) \cdot N_{over} $$

>Hvis X1 = 0 _og_ X2 = 1

$$N_{A_{over}} = (A_{over} - H_u) \cdot N_{over} $$

Hvor:

* X1: Indikerer om der nedmuldes halm = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!G1&action=embedview)
* X2: Indikerer om halm er angivet som direkte input = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!S1&action=embedview)
* N<sub>over</sub>: N indhold i afgrøderester over jorden = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!N1&action=embedview) [kg N/kg]
* H<sub>f</sub>: Halmfraktion ift. udbytte = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!Q1&action=embedview) [ts]
* U: Udbytte [kg ts/ha _eller_ FE/ha] = Læses fra MO ellers [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!F1&action=embedview) [kg/ha, FE/ha]
* T: Tørstoffraktion af høstet produkt = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!I1&action=embedview)
* H<sub>u</sub>: Halmudbytte = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!R1&action=embedview) [kg ts]


### **Beregning af afgrøderester over jorden, A<sub>over</sub>, afhænger af afgrødetypen**

For nogle afgrøder bruges udbytte + halmudbytte til beregning af afgrøderest (X = 1), for andre ikke (X = 0). 

>Hvis X3 = 0

$$A_{over} = U \cdot T \cdot S + I$$

>Hvis X3 = 1

$$A_{over} = (U \cdot T + H_u) \cdot S + I$$

Hvor:

* X3: Indikerer om udbytte + halmudbytte bruges til beregning af afgrøderest = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!T1&action=embedview)
* S: Slope = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!K1&action=embedview)
* I: Intercept = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!L1&action=embedview)

### **Beregning af N i afgrøderester under jorden, N<sub>A<sub>under</sub></sub>, afhænger af afgrødetypen**

>Hvis X4 = 0

$$N_{A_{under}} = (U \cdot T + A_{over}) \cdot F \cdot N_{under} $$

>Hvis X4 = 1

$$N_{A_{under}} = A_{over} \cdot F \cdot N_{under}$$


Hvor:

* X4: Indikerer om udbyttet nedmuldes = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!X1&action=embedview)
* F: Forhold underjordisk biomasse til overjordisk biomasse = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!P1&action=embedview)
* N<sub>under</sub>: N indhold i afgrøderester under jorden = [Tabelværdi](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!O1&action=embedview) [kg N/kg]




### **Omregning til CO<sub>2</sub>e:**

$$CO_2e = N_{afgrøderester}   \cdot EF_{N_2O} \cdot \frac{44}{28} \cdot \theta_{N_2O-CO_2}$$
Hvor: 

 * EF<sub>N<sub>2</sub>O</sub>: Emissionsfaktor for N<sub>2</sub>O = 0,01
 * $\theta$ N<sub>2</sub>O-CO<sub>2</sub></sub>: Omregningsfaktor N<sub>2</sub>O til CO<sub>2</sub> = 298
