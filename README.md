# Fitting of the Oscillatory Rheology Data
This program fits an oscillatory shear rheology dataset containing small and large amplitudes to the constitutive model developed by Ruud van der Sman. The research paper is available [here](https://doi.org/10.1016/j.foodhyd.2023.109586).  


## Data Reading
- data_reading.ipynb : the script to read the specified data file in the ./experimental data
- ./data_reading : is the directory where the data read by the data_reading.ipynb is stored.
- data_reading_inputs.py : input file for data_reading.ipynb, it is automatically read in the data_reading.ipynb.
 
## Data Fitting
fitting.ipynb :  the fitting script, which takes fitting_inputs.py as an input. 

### PF60 W18
Data: 
/Users/yagmurbalabanli/GitLab/LAOS_fit_lauren/potato_flake_inks/data_reading/arrays_2025_05_08_11_14_humanreadable.py

Parameter files: 2025_05_09_15_52

### PF60 W22
Data:
/Users/yagmurbalabanli/GitLab/LAOS_fit_lauren/potato_flake_inks/data_reading/arrays_2025_05_08_14_14_humanreadable.py

Parameter Files: 2025_05_09_16_01

### PF60 W25
Data:
/Users/yagmurbalabanli/GitLab/LAOS_fit_lauren/potato_flake_inks/data_reading/arrays_2025_05_08_14_42_humanreadable.py

Parameter Files: 2025_05_09_12_05
