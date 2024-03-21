This is the repository for the second project of UVA DS 4002 project group 6: Miranda Khoury, Georgia Davidson, and Brian Bippert. This project involves conducting Granger and ARIMA tests on our datasets in order to determine possible correlation, allowing certain values to be predicted given other values.

## Section 1: Software and platform

Software used: We used the coding language R and IDE software RStudio to perform correlation analysis on our purchasing power parity and inflation rate dataframes. 

Add-on packages installed with software:
- readr
- ggplot2
- lmtest
- forecast

Platform: We used the platform Windows for our project.



## Section 2: Map of documentation
 
Data folder:
- Data Appendix.pdf
- Purchasing_power_parity.csv
- inflation_%_per_yr.csv


Output folder:
- inflation_%_per_yr.csv
- canada_inflation_residuals.png
- canada_ppp_forecast.png
- canada_ppp_residuals.png
- inflation.jpg
- inflation_granger_p_vals.png
- inflation_granger_p_vals.png
- mexico_inflation_forecast.png
- mexico_inflation_residuals.png
- mexico_ppp_forecast.png
- mexico_ppp_residuals.png
- ppp_canada.jpg
- ppp_mexico.jpg
- ppp_on_inflation.csv
- ppp_us.jpg
- us_inflation_forecast.png
- us_inflation_residuals.png


Scripts folder:
- Inflation_Granger_and_Intracountry_ARIMA.Rmd
- Time_Series_Inflation.Rmd



## Section 3: Instructions for reproducing results

To replicate our results, first download both of the .csv files in the Data folder. If not already installed, install R and RStudio. You can download R by selecting one of the mirrors from this site (https://cran.r-project.org/mirrors.html) and selecting “Download R for [your operating system]”. You can download RStudio from this site (https://posit.co/download/rstudio-desktop/).

Download the two script files from the Scripts folder entitled Inflation_Granger_and_Intracountry_ARIMA.Rmd and Time_Series_Inflation.Rmd, and ensure that the script files are in the working directory of RStudio. To do this, either move the files into the current working directory or set the working directory to the location where the file is stored. Getwd() will return the current working directory and setwd() will change the working directory. Open both files. Change the paths in the Import Data cells in the code blocks that start on lines 19 and 25, and 15 and 16 respectively. Run all cells of the R Markdown scripts. The script will automatically read in the data files, clean them, perform exploratory analysis, and perform correlation analysis and related hypothesis testing. Cross reference the outputs provided against the outputs uploaded in the Outputs folder to verify the results.




