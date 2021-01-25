# Data file descriptor
Comparison of drug follow-up time in randomized controlled trials (RCT) registered in
ClinicalTrials.gov vs patient drug exposure times calculated from the Commercial Claims
and Encounters (CCAE) database. All durations are in days. 

## Columns
`drug_concept_id`: OMOP concept ID of drug ingredient  
`num_trials`: Number of RCTs investigating this drug ingredient  
`num_persons_RCT`: Total number of participants enrolled across RCTs  
`min_time_RCT`: Minimum follow-up time across RCTs  
`max_time_RCT`: Maximum follow-up time across RCTs  
`median_time_RCT`: Median follow-up time across RCTs  
`p10_time_RCT`: 10th percentile follow-up time across RCTs  
`p25_time_RCT`: 25th percentile follow-up time across RCTs  
`p75_time_RCT`: 75th percentile follow-up time across RCTs  
`p90_time_RCT`: 90th percentile follow-up time across RCTs  
`num_persons_ccae`: Number of patients exposed to this drug ingredient in CCAE  
`min_time_CCAE`: Minimum patient drug exposure time in CCAE  
`max_time_CCAE`: Maximum patient drug exposure time in CCAE  
`median_time_CCAE`: Median patient drug exposure time in CCAE  
`p10_time_CCAE`: 10th percentile patient drug exposure time in CCAE  
`p25_time_CCAE`: 25th percentile patient drug exposure time in CCAE  
`p75_time_CCAE`: 75th percentile patient drug exposure time in CCAE  
`p90_time_CCAE`: 90th percentile patient drug exposure time in CCAE  
`num_person_gt_minRCT`: Number of patients with drug exposure times greater than the minimum RCT follow-up time  
`num_person_gt_maxRCT`:	Number of patients with drug exposure times greater than the maximum RCT follow-up time  
`num_person_gt_medianRCT`: Number of patients with drug exposure times greater than the median RCT follow-up time  
`num_person_gt_p10RCT`: Number of patients with drug exposure times greater than the 10th percentile RCT follow-up time  
`num_person_gt_p25RCT`:	Number of patients with drug exposure times greater than the 25th percentile RCT follow-up time  
`num_person_gt_p75RCT`:	Number of patients with drug exposure times greater than the 75th percentile RCT follow-up time  
`num_person_gt_p90RCT`:	Number of patients with drug exposure times greater than the 90th percentile RCT follow-up time  
`pct_person_gt_minRCT`: Percent of patients with drug exposure times greater than the minimum RCT follow-up time  
`pct_person_gt_maxRCT`: Percent of patients with drug exposure times greater than the maximum RCT follow-up time  
`pct_person_gt_medianRCT`: Percent of patients with drug exposure times greater than the median RCT follow-up time  
`pct_person_gt_p10RCT`: Percent of patients with drug exposure times greater than the 10th percentile RCT follow-up time  
`pct_person_gt_p25RCT`: Percent of patients with drug exposure times greater than the 25th percentile RCT follow-up time  
`pct_person_gt_p75RCT`: Percent of patients with drug exposure times greater than the 75th percentile RCT follow-up time  
`pct_person_gt_p90RCT`: Percent of patients with drug exposure times greater than the 90th percentile RCT follow-up time  
`concept_name`: drug ingredient (concept name from OMOP Vocabulary)  
`atc1_name`: Anatomical Therapeutic Chemical (ATC) classifiation system 1st level  
