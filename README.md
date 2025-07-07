
Title: RDM Jumpstart Project 

This R project was used throughout the RDM jumpstart course offering in May 2025. It contains the data, scripts, and outputs generated throughout the course. The scripts are mainly R-markdown files with the relevant code as well as my personal notes. More information about the course and the project indtructions can be found on the following site: https://alliance-rdm-gdr.github.io/rdm-jumpstart/index.html 

The following readme information was generated on 2025-05-08 by Nick Rochlin.

Description: This project space will be used throughout the week to track and save the outputs from the Research Data Management Jumpstart, delivered online from May 12-16, 2025. 

The project space has 6 main folders:

1) data:  

This folder comes populated with the dataset that will be used throughout the week (described in more detail below), and will also be a place for your to save and backup the derived datasets that you clean and explore throughout the Jumpstart.  You can name the data files you generate however you'd like, noting that there will be a session on file naming on the afternoon of day 1 to guide you through some best practices

File list:

  * timeuse_day1_na.csv
      Description: Derived dataset from the General Social Survey, Cycle 29, 2015 [Canada]: Time Use dataset, after having removed many variables and accounting for NA values practical purposes.
      
 
2) docs: 

This folder is where you can find documentation for all the files withing the RDM Jumpstart OSF collection.

File list:

  * GSS29_PUMF_main_v3.pdf
      Description: The data dictionary from the original General Social Survey, Cycle 29, 2015 [Canada]: Time Use dataset.  This is here only as a reference.
  
  js_DMP.md
      A data management plan for the RDM Jumpstart series, written in markdown for editing.  To view the DMP on the RDM Jumpstart website, see [here](https://alliance-rdm-gdr.github.io/rdm-jumpstart/6-EXT-ProjectDMP.html)
      
  * js_TimeUse_Dictionary.md
      Description: A markdown version of the data dictionary for Timeuse_day1_na.csv, which can be edited and updated.
      
  * js_TimeUse_dictionary.pdf
      Description: A PDF version of the data dictionary for Timeuse_day1_na.csv, for easier viewing compared to the markdown document.
  
  * js_TimeUse_deposit_README.md
      Description: An example of a README document that will be deposited with other materials on day 5.
      
  * README-template.md
      Description: A template for a README document that can be used to accompany your data deposit on day 5, as well as a general template that you can use going forward.  [Template source](https://data.research.cornell.edu/data-management/sharing/readme/) 
    
    
3) outputs

This folder will be a place for you to put all outputs from your work this week that aren't code or data, which include visualizations, and .html/.pdf outputs generated from the RMarkdown file.  You are free to name your files as you see fit.


4) resources

This folder contains resources to support you throughout the week, in case you aren't able to complete all the exercises in the sessions.  There are 2 sub-folders in this folder:

*data:*

  * This folder contains datasets that can be used at the start of each session, in case you weren't able to complete all the exercises in the previous session(s).
      
* File list:
      
    * timeuse_day2.csv
    Description: The file generated at the end of the "R: First Steps" session and used at the beginning of the "R: Data                    Structures" session.
            
    * timeuse_day2.RData
    Description: The RData version of timeuse_day2.csv
        
    * timeuse_day3-1.RData: The file generated at the end of the "R: Data Structures" session, and used at the beginning of the "R:         Filter and Select" session.
        
    * timeuse_day3-2.RData: The file generated at the end of the "R: Filtering and Selecting" session, and used at the beginnig of          the "R: Data Visualization" session.
            
*scripts:*

  * This folder contains the completed script from the whole RDM Jumpstart series.
      
* File list:
    * script_js_timeuse_2025.Rmd
    Descroption: This file contains the entire RMarkdown script used throughout the whole week of the RDM Jumpstart series.
      

5) scripts: 

This folder is a place for you to save and backup the RMarkdown script that you create throughout the week.  You are free to name your scripts as you see fit.


6) tmp

A `tmp` folder is common in most projects, and represents a place for temporary files that you don't need to keep.  You are going to generate some extra files that you won't need this week (.html / .pdf files from the RMarkdown file), and this will be a place that you can place them to keep your main folders clean, and that can be deleted after the project or whenever you choose.



Data Source Information:

Social and Aboriginal Statistics Division, 2023, "General Social Survey, Cycle 29, 2015 [Canada]: Time Use, Main File", https://doi.org/10.5683/SP3/RDS0CK, Borealis, V1, UNF:6:gNUeH68ZNXHdGnqBlkUbrw== [fileUNF]

For practical purposes, we will only be using a subset of variables from the dataset, but for more information about the data and access to the full dataset, visit the DOI referenced in the above citation.

    
    
    
    
    
    
    
    
    
