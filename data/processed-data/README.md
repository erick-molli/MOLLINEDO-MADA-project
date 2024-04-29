This folder contains all the processed data, which is usually the products obtained from the data cleaning/exploring/analysis. These files will be used to run additional codes, if files are generated, they shouldn't be deleted. However, these files could be updated as necessary from changes in the data cleaning, data exploring or data analysis codes.

## Important data files

These are the generated data files used for analysis:

*`concentration.rds` which contains the final concentrations by each element, for each sample filter
*`uncertainty.rds` which contains the uncertainties by each element for each sample filter. These should be matching in order with the concentration.rds file.
*`hapin-final.rds` which is the final data frame used for all the statistical analyses, mainly for the modeling section.
*`hapin_blanks.rds` the file that contains all concentrations of each element for each blank filter.
*`hapin_samples.rds` is the uncleaned version file that contains all concentrations for the sample filters and other variables, it is used to obtain the `hapin-final.rds` file.

## Codebook for 'hapin_final.rds'

1.`filter_id`: ID of filter sample
2.`Mg`: Concentration of magnesium in filter sample (in ug/m3)
3.`Al`: Concentration of aluminum in filter sample (in ug/m3)
4.`Si`: Concentration of silicon in filter sample (in ug/m3)
5.`S`: Concentration of sulfur in filter sample (in ug/m3)
6.`K`: Concentration of potassium in filter sample (in ug/m3)
7.`Ca`: Concentration of calcium in filter sample (in ug/m3)
8.`Ti`: Concentration of titanium in filter sample (in ug/m3)
9.`Mn`: Concentration of manganese in filter sample (in ug/m3)
10.`Fe`: Concentration of iron in filter sample (in ug/m3)
11.`Zn`: Concentration of zinc in filter sample (in ug/m3)
12.`BC`: Concentration of black carbon in filter sample (in ug/m3)
13.`arm`: Study arm (Control or Intervention)
14.`stove`: Was a stove lit at some point in the last 24 hours? (Yes or No)
15.`smoke`: Did anyone smoke at some point in the last 24 hours? (Yes or No)
16.`coil`: Was a mosquito coil lit at some point in the last 24 hours? (Yes or No)
17.`trash`: Did anybody burned trash in the last 24 hours? (Yes or No)
18.`kerosene`: Did anybody used a kerosene lamp in the last 24 hours? (Yes or No)
19.`incense`: Was a candle or incense lit at some point in the last 24 hours? (Yes or No)
20.`generator`: Was there a corn mill or other type of generator used in the last 24 hours? (Yes or No)
21.`smoky`: Did anybody prepared smoked fish or meat in the last 24 hours? (Yes or No)
22.`crop`: Did anybody burned crop residues in the last 24 hours? (Yes or No)
23.`stove_other`: Was the participant exposed to smoke from stoves from other households? (Yes or No)
24.`pm25`: PM2.5 concentration in the filter sample (in ug/m3)
25.`fueltype`: Stove type based of type of fuel used (Biomass or LPG)
