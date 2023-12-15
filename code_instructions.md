{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "8289dd54-5a83-448c-b52c-698a7b5e1a75",
   "metadata": {},
   "source": [
    "# Instructions for retrieving and using code for the El Nno Project"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "ccb221c4-98f4-443e-99f0-d387f98c7f5e",
   "metadata": {},
   "source": [
    "## Code to download Sea Surface Height data from the NASA PODOCC website\n",
    "\n",
    "* Inside the jupyter_notebook is notebook_B. Inside notebook_B is a file called download_ssh_from_POAAC.\n",
    "* This code will allow you to download the sea surface height data\n",
    "\n",
    "## Code to download Sea Surface Temperature data from the NASA PODOCC website\n",
    "* Inside the jupyter_notebook is notebook_B. Inside notebook_B is a file called download_ssh_from_POAAC.\n",
    "* This code will allow you to download the sea surface height data"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "6da9302e-a99a-4ff7-b8a0-0e86d0cb6d32",
   "metadata": {},
   "source": [
    "## Code to generate SST color maps\n",
    "* Inside the jupyter_notebook is notebook_A. Inside notebook_A is a file called ms274_enso_sst_map.\n",
    "* This code will generate all of the SST color maps\n",
    "\n",
    "## Code to generate SST & SSH times-series, correlation coefficients, and the linear regression calculations\n",
    "* Inside the jupyter_notebook is notebook_A. Inside notebook_A is a file called final_project_sst_ssh_code.\n",
    "* This code generate all of the SST times-series, correlation coefficients, and linear regression calculations and plots"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "81e4f96d-3cf0-4003-83c1-f31276e0eeec",
   "metadata": {},
   "source": [
    "# Instructions for duplicating the data analysis in the SST color maps\n",
    "* use the file: ms274_enso_sst_map\n",
    "* The code is pretty much plug and play. All you need to do update the varible data_folder with you file_source \n",
    "* You can comment out the section regarading the file_path unless you want to see the variables in the data file\n",
    "* If you desire different time-series, just change the dates in the code to those that you are interested in analyizing\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "5f3c0aa8-9eca-47d0-9165-35d680fa294b",
   "metadata": {},
   "source": [
    "# Instructions for duplicating the data analysis for the SST & SSH time-series, correlation coefficients and the linear regressiion calculations.\n",
    "* use the file: final_project_sst_ssh_code\n",
    "* For simplicity, I included all the code to generate the SST & SSH data on the same file\n",
    "* The code is pretty much plug and play.\n",
    "* ***The instructions are the same for the sst as the ssh.  The only difference is the file path of the code***\n",
    "### There are three sections to the code\n",
    "* The first section is the time-series for the SST and SSH\n",
    "* Just change the data in the sst_data_folder and the ssh_data folder \n",
    "* This code is set up to read data in the Nino 3.4 region. You change this by chaning the coordinates in the code\n",
    "* If you desire different time-series, just change the dates in the code to those that you are interested in analyizing"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "7b01b85f-3734-469b-acb3-9d164c54f39e",
   "metadata": {},
   "source": [
    "# What to do if you have issues with the code\n",
    "* email me at seamus.jameson@sjsu.edu and will be happy to walk you through the code"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "04c9f059-b708-471b-86de-5a590837cba6",
   "metadata": {},
   "outputs": [],
   "source": []
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "ms274",
   "language": "python",
   "name": "ms274"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.10.12"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
