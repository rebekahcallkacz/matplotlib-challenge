# matplotlib-challenge: Pymaceuticals

Version: 1.0.0

Description
---------------
The purpose of this script is to analyze cancer drug trial data. 

## Background
In this study, ten cancer drugs were tested to observe if they had any effect on reducing tumor growth. 249 mice with SCC tumor growth were treated with one of the ten drug regimens for 45 days. Tumor volume was measured every 5 days. 

## Datasets
Two datasets were used in this analysis: mice metadata and study data which included tumor volume at the observed timepoints. One mouse was removed from the dataset due to conflicting observations at multiple timepoints for a total of 248 mice in the final analysis.

![alt text](https://github.com/rebekahcallkacz/matplotlib-challenge/blob/master/Pymaceuticals/Images/mousemetadata.jpg "Mouse Metadata")

![alt text](https://github.com/rebekahcallkacz/matplotlib-challenge/blob/master/Pymaceuticals/Images/studydata.jpg "Study Data")

## Analysis
When reviewing number of tumor volume measurements per drug, it seems that those with the most measurements (Capomulin and Ramicane) might be more promising since fewer datapoints suggests that mice may have died before the end of the study. 

![alt text](https://github.com/rebekahcallkacz/matplotlib-challenge/blob/master/Pymaceuticals/Images/datapointsperdrugtype.png "Datapoints per Drug")

Average final tumor volume for four of the drug regimens (Capomulin, Ramicane, Infubinol, Ceftamin) were calculated and compared. As can be seen from the box plot below, average tumor volumes were lower for Ramicane and Capomulin. 

![alt text](https://github.com/rebekahcallkacz/matplotlib-challenge/blob/master/Pymaceuticals/Images/finaltumorvolumeboxplot.png "Distribution of Final Tumor Volume")

As can be seen from the linear regression and scatter plot below, average final tumor volume seems to be positively linearly correlated to mouse weight (R^2=0.71). 

![alt text](https://github.com/rebekahcallkacz/matplotlib-challenge/blob/master/Pymaceuticals/Images/linearregressiontumorweight.png "Final Tumor Volume by Weight")

## Limitations
 

Contributors
----------------
Rebekah Callari-Kaczmarczyk

License and Copyright
--------------------------
&copy; Rebekah Callari-Kaczmarczyk