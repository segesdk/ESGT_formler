# **Diesel og maskinarbejde**

## Bedriftsaftryk


$$ CO_2e_{diesel} = (D \pm M) \cdot \theta_D$$

Hvor 

* D: Det totale dieselforbrug på bedriften = Input fra bruger  [L]
* θ<sub>D</sub>: Omregningsfaktor for diesel = 2,626 [kg CO<sub>2</sub>e/L]
* M: Maskinarbejde. Indkøbt maskinarbejde lægges til det totale dieselforbrug, mens solgt maskinarbejde trækkes fra. Maskinarbejdet opgives i kr og omregnes til L diesel med formlen:

$$ M = P \cdot \theta_M$$

Hvor 

* P: Prisen for maskinarbejde købt/solgt = Input fra bruger [kr]
* θ<sub>D</sub>: Omregningsfaktor for kr maskinarbejde til L diesel = 0,02 [L/kr]

## Produktaftryk

Produktaftrykket, P, for en afgrøde, a, findes ved at fordele den totale mængde diesel, D, vha. en fordelingsnøgle:

$$ P_{a, diesel} = \frac{H_a \cdot T_a}{\sum_{i=1}^n H_i \cdot T_i} \cdot (D \pm M) \cdot \theta_D$$

Hvor 

* H<sub>a</sub>: Det totale antal hektar på bedriften med afgrøde a = indlæses fra MO
* T<sub>a</sub>: Typetal for afgrøde a's dieselforbrug = Ses i [regnearket](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!V1&action=embedview)
* H<sub>i</sub>: Det totale antal hektar på bedriften med den i'te afgrøde = indlæses fra MO
* T<sub>i</sub>: Typetal for den i'te afgrødes dieselforbrug = Ses i [regnearket](https://seges.sharepoint.com/:x:/r/sites/GreenAction/_layouts/15/Doc.aspx?sourcedoc=%7BA8797CF8-D09C-4577-B972-E4D9C79AF9FF%7D&file=Afgr%C3%B8der_data_g%C3%B8dnings%C3%A5r%202020-2021_FOREL%C3%98BIG.xlsx&activeCell=%27Data%27!V1&action=embedview)
* n: Antal forskellige afgrøder på bedriften = indlæses fra MO




 