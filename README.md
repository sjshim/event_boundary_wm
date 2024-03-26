# event_boundary_wm

## data
All data are shared in data directory, under each Experiment. Data was cleaned to remove ID number related to participants' Prolific accounts as well as removing 'session', 'date', 'expName', 'psychopyVersion', 'OS', 'frameRate' columns.

## analysis_code
- exclusion.ipynb: Jupyter notebook containing code used to exclude participants based on performance accuracy for all three experiments. Outputs ../data/excluded_files_cleaned.csv
- RT_analysis.ipynb: Jupyter notebook containing code used to run RT analysis on boundary and non-boundary items and creating figures. Outputs exp{num}_boundary_rt_results.csv
- accuracy_analysis_and_figures.ipynb: Jupyter notebook containing code used to run temporal order accuracy analysis and creating figures. Outputs exp{num}_results_withRT.csv