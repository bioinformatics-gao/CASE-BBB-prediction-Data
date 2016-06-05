The Data fold contains three sub-folds and each sub-fold contains several tables
 
1)  Supplementary-data
     TableS1: Drug for Training and validation
           This table contains drug used in training and validation. The drug CID, Drug Name and permeability to Blood-Brain-Barrier (BBB+/-) and reference is listed.
     TableS2: High Level Group Terms for CNS Symptoms
           This table lists the drug side effects and drug indication terms used as features for machine leaning, totally 43 "High Level Group Terms" were listed.
     Table S3. Independent Test Data Set of Drugs Based on CNS Activity
           This table listes 161 drugs used for testing machine learning performance.  The drugs and associated chemical feature data was from the paper of Doniger               et al. (2002) J. Comp. Bio., 9, 849–864. 
     Table S4. BBB Permeability Prediction  for Drugs in SIDER Database
           This table is the prediction of BBB permeability of drugs listed in SIDER Database
     Table S5. Analysis for the predicted BBB+ drugs 
           This table contains clinical observation information from Drug.com and DrugBank database (03/2016) for the predicted BBB+ drugs

2)  Intermediate-data
     Inter-Table1-The HLGT-groups associated with each SOC in Nervous System Disorders SOC and Psychiatric Disorders SOC 
           All the Preferred Term (PT) under each 43 HLGT (TableS2) were listed in this Table.
     Inter-Table2-SideEffects (PT level) of Each Drug
           All Side effects associated with the drug were listed following the Drug CID
     Inter-Table3-Indications (PT level) of Each Drug
           All Indications associated with the drug were listed following the Drug CID
     Inter-Table4-Training and validation drugs with associated occurrence of side effects and indications
           "1" stands the side effects or indications associated with the drug, "0" stands not recorded
     Inter-Table5-Independent test data with associated occurrence of side effects and indications
           "1" stands the side effects or indications associated with the drug, "0" stands not recorded

3)  Data-in-the paper
     Table1-Performance of different kernels in SVM model
           This table contains data about training and validation with drug side effects for drug BBB permeability with different kernels in SVM models 
     Table2-Performance of different feature groups in SVM model
           This table contains data about training and validation with drug side effects, drug indications and their combination 
     Table3-The MOST weighted HLGT in the SVM model
     Table4-The LEAST weighted HLGT in the SVM model
     Table5-Prediction performance in independent data set
     Table6-Performance of chemistry & phenotype based prediction
           The drug chemical features and drug clinical phenotype were used as features for BBB permeability prediction   
     Table7-Category summary of 110 predicted BBB+ drugs
     Table8-List of default BBB- drugs predicted as BBB impermeable        

