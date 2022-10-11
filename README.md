# PPOL564 Slides and Activities

Repo for Georgetown McCourt's School of Public Policy's Data Science I (PPOL 564) in Fall of 2022


## Slides and Activities (Fall '22)

These are jupyter notebook-based activities to practice Python or other concepts, along with accompanying slides:

### Python basics

- [00_introclass.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/00_introclass.ipynb)
  - **Concepts covered**:
    - Creating variables
    - Checking types
    - Lists 
    - Basic list comprehension
    - Basic numpy arrays
  - **Slides**: [01_ppol564_f22_intro_pythonbasics.pdf](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/slides/fall_22/01_ppol564_f22_intro_pythonbasics.pdf)

### Data wrangling

- [01_pandas_datacleaning_blank.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/01_pandas_datacleaning_blank.ipynb)
  - **Data**: DC crime reports in 2020
  - **Concepts covered**:
    - Aggregation using `groupby` and `agg`
    - Lambda functions within aggregation
    - Recoding variables using `np.where`
    - Recoding variables using `np.select`
    - Recoding variables using `map` and dictionary
  - **Slides**: [02_ppol564_f22_datawrangling.pdf](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/slides/fall_22/02_ppol564_f22_datawrangling.pdf)
  - **Solutions**: [01_pandas_datacleaning_solutions.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/solutions/01_pandas_datacleaning_solutions.ipynb)

- [02_functions_part1_blank.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/02_functions_part1_blank.ipynb)
  - **Data**: DC crime reports in 2020
  - **Concepts covered**:
    - user-defined function to find matches within a broader pool of data
    - using list comprehension to apply a function iteratively over list elements 
   -  **Slides**: [03_ppol564_f22_userdefinedfunctions_part1.pdf](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/slides/fall_22/03_ppol564_f22_userdefinedfunctions_part1.pdf)
   -  **Solutions**: [02_functions_part1_solutions.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/solutions/02_functions_part1_solutions.ipynb)
  
- [03_plottingexamples_plotnine.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/03_plottingexamples_plotnine.ipynb)
  - **Data**: DC crime reports in 2020
  - **Concepts covered**:
    - Bar chart
    - Line graph
    - Coloring and/or faceting by group
 
- [04_latex_output_examples_blank.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/04_latex_output_examples_blank.ipynb)
  - **Data**: DC crime reports in 2020
  - **Concepts covered**:
    - Creating tables to export to LaTeX
    - Saving figures to export
    - Using user-defined function to iterate over entities and efficiently save many figures
    - **Solutions**: [04_latex_output_examples_solutions.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/solutions/04_latex_output_examples_solutions.ipynb)


- [05_reviewsession_blank.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/05_reviewsession_blank.ipynb)
  - **Data**: simulated data
  - **Concepts covered**:
    - Methods versus attributes
    - Reshaping using `pivot` and `pivot_table()`
    - User-defined functions and if/elif/else control flow
  - **Solutions**: [05_reviewsession_solutions.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/solutions/05_reviewsession_solutions.ipynb)

- [06_reshaping_merging_blank.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/06_reshaping_merging_blank.ipynb)
  - **Data**: San Diego business tax certificate data; Census NAICS code data
  - **Concepts covered**:
    - Reshaping between long and wide
    - Data cleaning such as extraneous rows/columns
    - Recasting join cols to allow join (e.g., converting `int` to character)
    - `pd.merge` and different types of exact joins using join keys
    - Post-merge diagnostics
   - **Slides**: [05_ppol564_f22_mergereshape.pdf](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/slides/fall_22/05_ppol564_f22_mergereshape.pdf)
   - **Solutions**: [06_reshaping_merging_solutions.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/solutions/06_reshaping_merging_solutions.ipynb)


- [07_regex_blank.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/07_regex_blank.ipynb)
- - **Data**: Food Research Action Center (FRAC) data on district and school's election of community eligibility provision (CEP) for Free or Reduced Price Lunch (FRPL)
   - **Concepts covered**: 
     - Pattern construction using `re` module
     - `re.sub` for replacement
     - `re.findall` 
     - `re.match` and how to work with match objects using `.group()`
     - Throughout, review of list comprehension 
    - **Slides**: [06_ppol564_f22_regex.pdf](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/slides/fall_22/06_ppol564_f22_regex.pdf)
    - **Solutions**: [07_regex_solutions.ipynb](https://github.com/rebeccajohnson88/PPOL564_slides_activities/blob/main/activities/fall_22/solutions/07_regex_solutions.ipynb)
