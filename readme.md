SZH2016 - auxiliary files to

M- Šmíd, F. Zapletal and J. Hančlová. Which Carbon Derivatives are Applicable in Practice? A Case Study
of a European Steel Company. Kybernetika vol 6, 2017.

Input.csv - future and spot prices time series

analysis.inp - Gretl script estimating the stochastic model

data.ods - spreadsheet computing scenarios, margins and some other results - see sheet "Results" (sheet "Input" is a copy of input.csv)

results.xlsx - results of the optimization



Workflow:

1. Run analysis.csv to produce the estimates of the model (Section 3)

2. Put the results into Data.Params

3. Solve the optimiization problems with parameters given by Table 2 and Data.Results and with the MC sample given in Data.Results. 

4. Copy the results of the optimizations into results.xlsx

Note: due to our agreement with the modelled steel company, we do not publish the GAMS script performing optimization (step 3) because it includes confidential data as its parameters.


Remark: source data for Table 4 find themselves in Data.Results.