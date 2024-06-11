# Comparative effects of pharmacological interventions for the acute management of migraine attacks in adults: a systematic review and network meta-analysis

Results can be reproduced using the dataset. Each outcome-specific folder includes the related dataframe (df.main - df.rds) ready to be imported into the R environment as an rds file (R Data Serialization format) and analysed using the functions of the [netmeta](https://cran.r-project.org/web/packages/netmeta/index.html) package. Before running any analyses, please exclude non-eligible arms (e.g., df <- df[(df$eligibility==1),]).

## Summary of the key functions used
- netmeta() (e.g., netmeta(pw.df, ref = 'placebo'))
- netmetabin() (e.g., netmetabin(pw.df, ref = 'placebo'))
- netsplit() (e.g., netsplit(nma))

Details on these and other functions are included in the reference manual for [netmeta](https://cran.r-project.org/web/packages/netmeta/index.html) package.

## Addendum
This information was added on 07-June-2024 as per request of The BMJ peer-reviewers. Further amended on 11-June-2024.