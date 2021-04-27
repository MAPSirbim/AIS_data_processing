# AIS_data_classification

This repository aims to describe a methodology to analyse AIS data broadcasted by fishing vessels.
The processing workflow aimed to identify individual fishing trips and classify them on a monthly basis according to predefined gear classes: bottom otter trawl (OTB), pelagic pair trawl (PTM), beam trawl (TBB), purse seine (PS), and “other” fishing (OTHER; including dredges and passive gears). The workflow was developed on a subset of known vessels whose fishing gears were manually assigned by visual inspection.
In this repository we also release:
•	a small subset of AIS signals broadcasted by vessels contained in the validated dataset (.csv,  one pair of  pelagic trawlers and one vessel for OTB, TBB, PS and “other”);
•	all the parameters required to process the data, such as  the input parameters needed to classify fishing trips (.csv) and the trained Random Forest model (.rds) used to finally assign the gear on a monthly basis and finalized to work in the Adriatic Sea; 
•	additional spatial layers required by the data processing (.shp).
A summary description of these data is provided in the Release data information section. 
