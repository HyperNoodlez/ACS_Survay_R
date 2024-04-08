# ACS/NHGIS Data cleaning notebook

This document presents a foundational notebook for the cleaning and filtering of IPUMS NHGIS datasets, primarily focusing on data derived from the American Community Survey (ACS). While this notebook is tailored to ACS data, its approach are adaptable to accommodate additional NHGIS datasets.

Acknowledging the inherent complexity of dataset manipulation, this notebook adopts a straightforward, manual approach to variable selection. This decision is informed by the necessity of reviewing the codebook to identify relevant variables, eschewing more automated, iterative methods. Despite this, the process is an opportunity for efficiency gains through the utilization of advanced LLMs such as GPT or Claude. These models could expedite variable identification by analyzing the codebook and generating precise variable selection commands.

Prompt for future refinement:
"Please rewrite variables ranging from 'Var_Start' to 'Var2_End' in the format of 'Var1', 'Var2', etc."

Variable Naming Standardization:

The current methodology for variable renaming—aimed at standardizing variable names across survey iterations, which often see names change—relies on a rudimentary, forceful approach. While functional, this strategy is earmarked for future refinement to achieve a more sophisticated, perhaps automated, solution.
