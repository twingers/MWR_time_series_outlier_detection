# MWR_time_series_outlier_detection
This workbook is currently only developmental code for outlier detection analysis.  This included creating code that can pull data from a PI data historian, generating synthetic data, creating static and dynamic plots, outlier analysis, and anomaly detection for time series data.

The primary purpose for this repository if for cleaning online sensor, process and laboratory data that is collected at a wastewater treatment plant.  Most data is place into a OSI PI historian database and the data is quite dirty.  Outlier and anomaly detection will be used to:
* Detect sensor drift,
* Data replacement for when equipment is offline,
* Data replacement for maintenance downtime,
* Outlier analysis for laboratory data analysis,
* Determination for equipment repair

## Outlier Analyses
* IQR with option to remove data that fail to a max and/or minimum value

## Anomaly Detection Analyses

## Current plots:
* boxplot
* histogram
* line plot that shows outliers