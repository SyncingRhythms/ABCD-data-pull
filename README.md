# Data Pull and Wrangle for the Adolescent Brain Cognitive Development (ABCD) study

I wrote custom python functions and code to flexibly pull data derivatives from a local directory of the ABCD Study 5.1 Data release.

Based on a user-provided input file (csv or excel) with at least 2 columns specifying the desired Tables and Variables ([example file](fmri-reward-activation-suicide/abcd_mid_tfmri_pull.xlsx)), the script will search subdirectories to find tables, select requested derivative variables, flexibily perform quality control processing for any MRI variables, complete data integrity checks, clean and wrangle data, and wide transform dataframe to represent collection waves in columns for analysis. 

This processing is currently conducted across two jupyter notebooks that are adapted to the specific pull request, generally named: 
1) 'ABCD_Data_pull_ ... .ipynb'
2) 'ABCD_wide_transform_ ... .ipynb'

Examples of two data pulls and transfroms are included in the two folders within.