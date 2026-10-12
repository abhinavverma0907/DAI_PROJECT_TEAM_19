# Our research questions

| Research question | Data needed | Statistical technique |
|---|---|---|
| Do gold-price increases coincide with changes in dowry-death rates? | Gold prices + NCRB | Correlation, regression |
| Are there delayed associations between gold-price changes and dowry deaths? | Historical gold prices + NCRB | Lagged regression |
| Do relationships differ across Indian states? | State-wise NCRB + socioeconomic indicators | Panel-data analysis |
| Does female education modify the relationship? | NCRB + education indicators | Interaction regression |
| Are gold-price changes associated with other forms of domestic violence? | Gold prices + NCRB/NFHS | Regression, subgroup analysis |


# Data set

| Research question | Data needed | Statistical technique |
|---|---|---|
| Do gold-price increases coincide with changes in dowry-death rates? | Gold prices + NCRB | Correlation, regression |
| Are there delayed associations between gold-price changes and dowry deaths? | Historical gold prices + NCRB | Lagged regression |
| Do relationships differ across Indian states? | State-wise NCRB + socioeconomic indicators | Panel-data analysis |
| Does female education modify the relationship? | NCRB + education indicators | Interaction regression |
| Are gold-price changes associated with other forms of domestic violence? | Gold prices + NCRB/NFHS | Regression, subgroup analysis |

Finding crime records from NCRB

Historical gold prices from RBI database and World Bank 

Commodity Markets *Pink Sheet*

Data about domestic violence and health from DHS Program surveys in India

Kaggle data "Crimes against women in India" and "Gold price in India"


# Additional research

| Paper | Research focus | Relevance |
|---|---|---|
| *Dowry Deaths: A Neglected Public Health Issue in India* (2011) | Dowry deaths and socioeconomic factors | Helps identify control variables |
| *The Economics of Dowry and Brideprice* — Siwan Anderson (2007) | Economic explanations for marriage payments | Theoretical foundation |
| *The Rise of Dowry in India* — Vijayendra Rao (1993) | Historical changes in dowry payments | Explains changes in dowry practices |
| *Terror as a Bargaining Instrument: A Case Study of Dowry Violence in Rural India* — Bloch and Rao (2002) | Violence and bargaining over dowry | Helps explain possible mechanisms |
| *Saving for Dowry: Evidence from Rural India* (2022) | Household savings and dowry obligations | Connects financial conditions with dowry |

# Regression

\[
D_{s,t}=
\alpha_s+
\beta_1G_t+
\beta_2X_{s,t}+
\gamma t+
\epsilon_{s,t}
\]

\(D_{s,t}\): Dowry-death rate. 

\(G_t\): Change in gold prices.

\(X_{s,t}\): Socioeconomic variables.

\(\alpha_s\): State fixed effects.

\(\gamma t\): Common linear time trend.