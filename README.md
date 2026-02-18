# IBD_subtype_discovery
We developed a novel proof-of-concept dual-encoder deep learning model to predict inflammatory bowel disease progression using longitudinal multi-omics data from 130 patients and over 1,600 samples. Using Gaussian mixture modeling on trajectory features, we identified three molecularly distinct Crohn’s disease subtypes and validated these findings with transcriptomic inflammation levels (p = 0.0017). Additionally, we discovered a high-risk subgroup representing 10% of patients with a 40% elevation in molecular inflammation, providing the potential for early treatment stratification and advancing precision medicine approaches in IBD. Future works including further cross-validation using more datasets, which would in turn enrich subtype results. 

All results are explained and shown in the notebooks, and should be read in the following order: 
1. dual_encoder_training
2. dual_encoder_validation
3. subtype_clustering
4. subtype_validation 
