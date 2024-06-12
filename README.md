# Title, abstract, and keywords: a practical guide to maximise the visibility and impact of academic papers

This repository contains the data, code, and other materials used for this project. We recommend navigating those documents using the knitted page, at https://p-pottier.github.io/keywords_to_success/

To cite this data or code, please use: *Pottier, P., Lagisz, M., Burke, S., Drobniak, S. M., Downing, P. A., Macartney, E. L., ... & Nakagawa, S. (2023). Title, abstract, and keywords: a practical guide to maximise the visibility and impact of academic papers. Zenodo* [![DOI](https://zenodo.org/badge/696517502.svg)](https://zenodo.org/doi/10.5281/zenodo.11593509)

Below is a description of the architecture of the different folders. Please don't hesitate to contact Patrice Pottier (p.pottier@unsw.edu.au) if you need assistance navigating these documents. We highly recommend contacting us if you are to re-use our data or analyses in future studies.

### data 

* `Survey_journal_guidelines.csv`: Data from the survey of journal policies
* `Processed_data_survey_journal_guidelines.csv`: Processed data from the survey of journal policies. This includes some inferences of title word limits, and the renaming and cleaning of columns and journal names.
* `Studies_to_screen_for_article_type.csv`: Sample of studies for which abstracts differ by at least 25 words from the abstract word limit imposed by journals. These studies were screened manually in Rayyan to identify and exclude non-standard article types.
* `Included_studies_after_screening.csv`: Included studies (standard article types) after screening `Studies_to_screen_for_article_type.csv`.
* `Processed_data_study_samples.csv`: Processed data from samples of ~25 studies retrieved from 230 journals in ecology and evolutionary biology.

### fig 

* `figure_3.png`: Output file for figure 3
* `figure_3A.png`: Output file for figure 3A
* `figure_3B.png`: Output file for figure 3B

### R 

* `Data_processing_and_text_mining.Rmd`: Code used to process the survey data and study samples, mine the text, and produce data visualisations
* `Data_processing_and_text_mining.html`: Knitted code 

### samples_ecoevo_journals

This folder contains all the bibliographic files used to gather study samples from ecology and evolutionary journals 

* `first_list_missing_journals.csv`: This file contains the list of journals missing from the first string
* `second_list_missing_journals.csv`: This file contains the list of journals missing from the second string
* `third_list_missing_journals.csv`: This file contains the list of journals missing from the third string
* `fourth_list_missing_journals.csv`: This file contains the list of journals missing from the fourth string
* `fifth_list_missing_journals.csv`: This file contains the list of journals missing from the sixth string

#### 1st_string

* `wos_first_string_20230911_1-1000.bib`: bibliographic file containing the first 1000 results from the first string
* `wos_first_string_20230911_1001-2000.bib`: bibliographic file containing the results 1001-2000 from the first string
* `wos_first_string_20230911_2001-3000.bib`: bibliographic file containing the results 2001-3000 from the first string
* `wos_first_string_20230911_3001-4000.bib`: bibliographic file containing the results 3001-4000 from the first string
* `wos_first_string_20230911_4001-5000.bib`: bibliographic file containing the results 4001-5000 from the first string
* `wos_first_string_20230911_5001-5785.bib`: bibliographic file containing the results 5001-5785 from the first string

#### 2nd_string

* `wos_second_string_20230911_1-1000.bib`: bibliographic file containing the first 1000 results from the second string
* `wos_second_string_20230911_1001-2000.bib`: bibliographic file containing the results 1001-2000 from the second string
* `wos_second_string_20230911_2001-3000.bib`: bibliographic file containing the results 2001-3000 from the second string
* `wos_second_string_20230911_3001-4000.bib`: bibliographic file containing the results 2001-3000 from the second string
* `wos_second_string_20230911_4001-4120.bib`: bibliographic file containing the results 2001-3000 from the second string

#### 3rd_string

* `wos_third_string_20230911_1-1000.bib`: bibliographic file containing the first 1000 results from the third string
* `wos_third_string_20230911_1001-1927.bib`: bibliographic file containing the remaining results from the third string

#### 4th_string

* `wos_fourth_string_20230911_1-1000.bib`: bibliographic file containing the first 1000 results from the fourth string
* `wos_fourth_string_20230911_1001-1253.bib`: bibliographic file containing the remaining results from the fourth string

#### 5th_string

* `wos_fifth_string_20230911_1-247.bib`: bibliographic file containing all results from the fifth string

#### 6th_string

* `wos_sixth_string_20230911_1-1000.bib`: bibliographic file containing the first 1000 results from the sixth string
* `wos_sixth_string_20230911_1001-2000.bib`: bibliographic file containing the results 1001-2000 from the sixth string
* `wos_sixth_string_20230911_2001-2473.bib`:bibliographic file containing the remaining results from the sixth string

#### 7th_string

* `wos_seventh_string_20230911_1-824.bib`: bibliographic file containing all results from the seventh string

#### Multidisciplinary_journals 

* `biological_reviews.bib`: bibliographic file containing the sample of studies from Biological Reviews
* `communications_biology.bib`: bibliographic file containing the sample of studies from Communications Biology
* `current_biology.bib`: bibliographic file containing the sample of studies from Current Biology
* `elife.bib`:  bibliographic file containing the sample of studies from eLife
* `nature.bib`: bibliographic file containing the sample of studies from Nature
* `nature_climate_change.bib`: bibliographic file containing the sample of studies from Nature Climate Change
* `nature_communications.bib`: bibliographic file containing the sample of studies from Nature Communications
* `philosophical_transactions_biological_sciences.bib`: bibliographic file containing the sample of studies from Philosophical Transactions of the Royal Society B
* `plos_biology.bib`: bibliographic file containing the sample of studies from Plos Biology
* `pnas.bib`: bibliographic file containing the sample of studies from Proceedings of the National Academy of Sciences of the United States of America
* `science.bib`: bibliographic file containing the sample of studies from Science
* `science_advances.bib`: bibliographic file containing the sample of studies from Science Advances
* `scientific_reports.bib`: bibliographic file containing the sample of studies from Scientific Reports



