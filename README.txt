README file
QRS detection and heartrate calculation
1. Required libraries- matplotlib, numpy, csv, scipy.
2. Download the dataset from https://www.physionet.org/cgi-bin/atm/ATM with parameters: length-to end, time format- seconds, data format- standard, export signals as CSV.
3.Delete the first 2 rows of your csv before giving input.
4. Paste the path to the .csv file in the 3rd block of the code.
5. Observe the signal plot after integration, and set a suitable threshold in the find_peaks function. For record 117, the threshold can be taken as 0.003
