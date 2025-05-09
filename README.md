# Fitting of the Oscillatory Rheology Data
This program fits an oscillatory shear rheology dataset containing small and large amplitudes to the constitutive model developed by Ruud van der Sman. The research paper is available [here](https://doi.org/10.1016/j.foodhyd.2023.109586).  


## Data Reading
- data_reading.ipynb : the script to read the specified data file in the ./experimental data
- ./data_reading : is the directory where the data read by the data_reading.ipynb is stored.
- data_reading_inputs.py : input file for data_reading.ipynb, it is automatically read in the data_reading.ipynb.
 
## Data Fitting
fitting.ipynb :  the fitting script, which takes fitting_inputs.py as an input. 

### SP60 W18
Data: 
/Users/yagmurbalabanli/GitLab/LAOS_fit_lauren/protein_inks/data_reading/arrays_2025_05_09_09_14_humanreadable.py

Parameter files: 2025_05_09_10_49

### SP60 W22
Data:
/Users/yagmurbalabanli/GitLab/LAOS_fit_lauren/protein_inks/data_reading/arrays_2025_05_09_09_17_humanreadable.py

Parameter Files: 2025_05_09_10_35

### SP60 W25
Data:
/Users/yagmurbalabanli/GitLab/LAOS_fit_lauren/protein_inks/data_reading/arrays_2025_05_09_11_47_humanreadable.py

Parameter Files: 2025_05_09_11_50

