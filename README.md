# BSRN_hour-averages
- This is a macro-activated workbook for use in Microsoft Excel.
- The main objective of BSRN_hour-averages" is to calculate hourly-average values from minute data in .dat files downloaded from NSRN (Baseline Surface Radiation Network); http://bsrn.awi.de/
- First download the chosen monthly .dat files from BSRN, either directly from ftp.bsrn.awi.de or indirectly using the "BSRN Toolbox". Then click the 'Import' button on worksheet 'Import' to post-process the files to this workbook. Note: Contact BSRN for a FTP password.
- The 'Import' macro checks data and flags any gaps or extreme values. The user can thus delete bad data. Quality-control checks include BSRN's recommended QC checks for extreme values, intercomparisons (direct, diffuse & global), and an additional test for time-shifted solar data.
- Small gaps (user specified length) are interpolated, while hours with long gaps of BSRN data are left empty.

### License
This work is licensed under a Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0), which means the following:
- Give appropriate acknowledgement/credit for its use,
- It may be used for commercial purposes,
- You can edit it but indicate all changes in the code,
- You can redistribute this code only under same license

### Author
Peter G. Schild (peter.schild@OsloMet.no), HiOA, Oslo, Norway, 2016-2018
