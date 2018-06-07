
Jun 5 2018

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

STATA SCRIPTS

ikea_namegroup.do

STATA OUTPUTS

ikea_namegroup_stata.xlsx

MATLAB SCRIPTS

ikea_namegroup.m
ikea_namegroup_pcp.m
ikea_namegroup_szs.m

MATLAB OUTPUTS

ikea_namegroup_all.xlsx
ikea_namegroup_pcp.xlsx
ikea_namegroup_szs.xlsx
ikea_namegroup_data.mat

SUMMARY

ikea_namegroup_summary.pdf

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++


ikea_namegroup_summary.pdf
description: summary documents of results
note: not necessary to look at the raw excel output; checking the document first would be sufficient

ikea_namegroup.do
description: modified do-file from the original
note: it takes the alt version of dataset, i.e., ikea_fill_alt_2018.dta

ikea_namegroup_stata.xlsx
description: output file from above do-file, containing the variables of interest
note: the first row of the excel file is variable name; the number of rows = #-of-(ijc) * #-of-(y)

ikea_namegroup.m
description: m-script-file that takes in the above output ikea_namegroup_stata.xlsx from do-file and perform main computation
note: some global variables are added so it would be easier if we want to use another set of groups, use another price change measure, etc.

ikea_namegroup_pcp.m
description: m-function-file that analyze the price change patterns within each group
note: it produces two row vectors: occurrence/magnitudes; the occurrence is the the total number of occurrence of each price change pattern, and the magnitudes are the average price level change magnitudes of each price change pattern

ikea_namegroup_szs.m
description: m-function-file that analyze the price change patterns across group sizes
note: it produces two matrix: row/mat; the first one gives variables at those percentiles, and the second one gives average of variables between thos percentiles.

ikea_namegroup_all.xlsx
description: output file from ikea_namegroup.m; it has two sheets, old and new; the old sheet is exactly the numerical dataset from stata do-file; the new sheet has additional columns of occurrence/magnitudes.

ikea_namegroup_pcp.xlsx
description: output file from ikea_namegroup.m; it has two sheets, occurrence and magnitudes.

ikea_namegroup_szs.xlsx
description: output file from ikea_namegroup.m; it has two sheets, row and mat.

ikea_namegroup_data.mat

