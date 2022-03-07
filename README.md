# GORGAS - Quantifying the effect of Human Population Mobility on Malaria risk in the Peruvian Amazon

## Study description
The impact of Human population movement (HPM) on the epidemiology of vector-borne diseases, such as malaria, has been described. However, there are limited data on the use of new technologies for the study of HPM in endemic areas with difficult access such as the Amazon. In this study conducted in rural Peruvian Amazon, we used self-reported travel surveys and GPS trackers coupled with a Bayesian spatial model to quantify the role of HPM on the malaria risk. By using a densely sampled population cohort, this study highlighted the elevated malaria transmission in a riverine community of the Peruvian Amazon. We also found that the high connectivity between Amazon communities for reasons such as work, trading or family plausibly sustain such transmission levels. Finally, by using multiple human mobility metrics including GPS-trackers, and adapted causal inference methods we identified for the first time the effect of human mobility patterns on malaria risk in rural Peruvian Amazon. This study provides evidence of the causal effect of HPM on malaria that may help to adapt current malaria control programs in the Amazon.

![](https://github.com/healthinnovation/GORGAS/blob/main/Figures/Fig%203.png)

> A. Cumulative distance and time traveled by subcohort participants during the whole study by infection status. B. Distance and time traveled weekly by participants in the subcohort during the whole study by infection status. C. Trajectories of selected participants outside the village taking into account the type of mobility pattern performed and the distance from Gamitanacocha (Red buffer: 3 km, Blue buffer: 10 km, Violet buffer: 20 km).

## Repository structure

1. Figure 
   - Fig 1.pdf - Map of the Amazon showing the location of Gamitanacocha and the main communities visited by the participants. 
   - Fig 2.pdf - Cases per species detected by PCR of the 50 participants. 
   - Fig 3.pdf - Cumulative distance and time traveled by subcohort participants and trajectories of selected participants outside the village taking into account the type of mobility pattern performed and the distance from Gamitanacocha 
   - Fig 3.png - Cumulative distance and time traveled by subcohort participants and trajectories of selected participants outside the village taking into account the type of mobility pattern performed and the distance from Gamitanacocha 
   - Fig 4.pdf - Forest plot of the models for each exposure applying the IPW for each type of model developed. 
   
2. model_data
   - df_cohortegeneral.gorgas.csv - cohort data for the IPTW models.
   - df_subcohorte.gorgas.csv - sub cohort data for the IPTW models.
   
4. .gitignore
5. 07.iptw_gorgas.Rmd - Rmarkdown of the models using IPTW
6. GORGAS.Rproj - R project file
7. README.md

## R environment and version

```
platform       x86_64-w64-mingw32          
arch           x86_64                      
os             mingw32                     
system         x86_64, mingw32             
status                                     
major          4                           
minor          0.3                         
year           2020                        
month          10                          
day            10                          
svn rev        79318                       
language       R                           
version.string R version 4.0.3 (2020-10-10)
nickname       Bunny-Wunnies Freak Out
```
