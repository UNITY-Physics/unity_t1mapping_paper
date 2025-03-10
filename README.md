# Multicenter T1 mapping

This repository contains the code to reproduce the figures in the paper "Repeatability and reproducibility of rapid T1 mapping of brain tissues at 64 mT: a multicentre study" (in preparation). Original source data is not shared, but compiled results in form of .csv files are shared in here.  

# Tabular Data 
The data are categorized into three groups: reproducibility in the phantom study, repeatability at a single site (both for phantom and in vivo studies), and reproducibility in vivo across different sites.
: contains the T1 values measured in the phantom from each site (3 repetitions per site);  
: contains the T1 values measured in phantom and in vivo data at six time points in one site;  
: contains the T1 values measured in vivo in 10 volunteers per site (2 repetitions per volunteer);  

# Notebooks to reproduce figures from paper

: contains the code to generate the phantom figures: Relaxation Rate vs Concentration in the phantom for each site (Figure 1) and average T1 values in two tubes at each site (Figure 2);  
: contains the code to generate the repeatability figures: Longitudinal analysis from one site, qualitatively (Figure 3) and quantitatively (Figure 4);  
: contains the code to generate the reproducibility figures: average T1 in white matter and cortex for each site (Figures 5), pooled average T1 map and pool standard deviation T1 map from all 60 volunteers (Figure 6), histograms of white matter and cortex across the whole brain for all volunteers (Figure 7a),  average T1 in deeper structures (Figure 7b) and Bland-Altman plot of T1 values in white matter and cortex for two consecutive runs and hemispheres (Figure 8).
