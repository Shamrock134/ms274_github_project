# Instructions for retrieving and using code for the El Nno Project

## Code to download Sea Surface Height data from the NASA PODOCC website

* Inside the jupyter_notebook is notebook_B. Inside notebook_B is a file called download_ssh_from_POAAC
* This code will allow you to download the sea surface height data

## Code to download Sea Surface Temperature data from the NASA PODOCC website
* Inside the jupyter_notebook is notebook_B. Inside notebook_B is a file called download_ssh_from_POAAC
* This code will allow you to download the sea surface height data

## Code to generate SST color maps
* Inside the jupyter_notebook is notebook_A. Inside notebook_A is a file called ms274_enso_sst_map
* This code will generate all of the SST color maps

## Code to generate SST & SSH times-series, correlation coefficients, and the linear regression calculations
* Inside the jupyter_notebook is notebook_A. Inside notebook_A is a file called final_project_sst_ssh_code
* This code generate all of the SST times-series, correlation coefficients, and linear regression calculations and plots

# Instructions for duplicating the data analysis in the SST color maps
* use the file: ms274_enso_sst_map
* The code is pretty much plug and play. All you need to do update the varible data_folder with you file_source
* You can comment out the section regarading the file_path unless you want to see the variables in the data file
* If you desire different time-series, just change the dates in the code to those that you are interested in analyizing

# Instructions for duplicating the data analysis for the SST & SSH time-series, correlation coefficients and the linear regressiion calculations
* use the file: final_project_sst_ssh_code
* For simplicity, I included all the code to generate the SST & SSH data on the same file
* The code is pretty much plug and play
* ***The instructions are the same for the sst as the ssh. The only difference is the file path of the code***
* 
### There are three sections to the code
* The first section is the time-series for the SST and SSH
* Just change the data in the sst_data_folder and the ssh_data folder
* This code is set up to read data in the Nino 3.4 region. You change this by chaning the coordinates in the code
* If you desire different time-series, just change the dates in the code to those that you are interested in analyizing
 