This folder contains all the processed data, which is usually the products obtained from the data cleaning/exploring/analysis. These files will be used to run additional codes, if files are generated, they shouldn't be deleted. However, these files could be updated as necessary from changes in the data cleaning, data exploring or data analysis codes.

These are the listed generated files of high importance:

*`concentration.rds` which contains the final concentrations by each element, for each sample filter
*`uncertainty.rds` which contains the uncertainties by each element for each sample filter. These should be matching in order with the concentration.rds file.
*`hapin-final.rds` which is the final data frame used for all the statistical analyses, mainly for the modeling section.
