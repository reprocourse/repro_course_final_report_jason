This project is divided into 3 key folders:
Code
Figures
And Raw_data


Code------
Analysis_NEUR_602.R has code to randomly select articles for inspection

power_analysis.R code to conduct power analysis
You can run four sets of analysis: 
T-test paired: uncomment line 5 and comment out line 8; comment out line 20,28 and 29; uncomment line 27; uncomment lines 51-55 and comment lines 58-62

Two sample t-test:uncomment line 5 and comment out line 8; uncomment line 20; comment out line 27 and 29; uncomment line 28; uncomment lines 51-55 and comment lines 58-62

ANOVA without correction :uncomment line 8 and comment out line 5; ; comment out line 20, 27 and 28; uncomment line 29; uncomment lines 58-62 and comment lines 51-55

ANOVA with correction (sample/numfactors) :uncomment line 8 and comment out line 5; ; uncomment line 20; comment out line 27 and 28; uncomment line 29; uncomment lines 58-62 and comment lines 51-55


The file baseline_correvtion_open_data_stefon does the analysis specified in the paper: uses a sliding window across many baselines to determine effects of choice on outcomes

To run the code, simply run as is, or alter the parameters on the upper section of the code to change how it runs (i.e. the electrodes chosen for analysis, the number and kind of baselines chosen etc).

Baseline_correction_repro_course does the same thing as the code above (but works with the data that is not available to everyone).


Raw_data-----------------
Baseline_correction_study_methods_checklist.csv detailed methods for baseline correction study (the one without open data)

ERP_data.xlsx data extracted from the studies

pubmed_results.csv all the articles found on pubmed

rand_selected.xlsx list of studies randomly selected for further analysis 

sample_sizes.csv data for R code to do power analysis with sample sizes

