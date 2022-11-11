# Data used to generate figures (Fig. 1 and Fig. 3)

All the data that are needed to generate Fig. 1 and Fig. 3 are located here. Among them, all the raw data collected are in the sub-folder ***raw***. The preprocessed data for these figures are:

   1. Figure 1. Global engagement in the Open Science movement.
   
      Data: **os_organizations.csv**;
   2. Figure 3. Number of reads of WeChat posts and articles for Open 4+ events. 
   
      Data: **cosn_events.csv**;
   
By Qing Wang and Yuanrui Zheng @ 2022.11.11

## 1. Data for Fig.1: os_organizations.csv

### Columns:

       country:  <string>, the abbreviation of the country; 

       rep_code: <string>, the 3 letter country code; 

       developed: <boolean>, whether this country is develped or not {1: developed, 2: developing}; 

       platform: <string>, OS organization name; 

       full_name: <string>,  the full name of the country; 

### Search Stratege Of the fFive OS Organizations

- Open Science GrassRoots Networks
  - Searching Date: 2022.3.15
  - [Link](https://groups.google.com/a/cos.io/g/network-of-open-science-grassroots-networks)
- Center For OpenScience
  - Searching Date: 2022.3.5
  - [Link](https://www.cos.io/communities/ambassadors)
- UK Reproducibility Networks and its affiliated organizations
  - Searching Date: 2022.3.26
  - [Link](https://www.ukrn.org/community/)
- ReproducibiliTea
  - Searching Date: 2022.3.29
  - [Link](https://reproducibilitea.org)
- Society For The Improvement Of Psychological Science(SIPS)
  - Searching Date: 2022.4.19
  - [Link](https://improvingpsych.org/committees/)

## 2. Data for Fig.3 data: os_organizations.csv

### Columns

       Events:  <string>, the name of this OS event; 

       Date: <date>, the date of this OS event; 

       Reads: <int>, the Number of reads of the event posts; 

       Topic: <string>, The event topic (in Chinese); 
