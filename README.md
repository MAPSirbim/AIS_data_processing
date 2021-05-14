


Release notes
================

# Overview

This R code aims to analyze Automatic Identification System (AIS) data.

(Galdelli et al. ([2018](#ref-Galdelli2018)))

<p>

The processing workflow was developed on historical annotated data of the
 Adriatic Sea and aims to (i) identify individual fishing trips and (ii) 
 classify them on a monthly basis according to 5 predefined gear classes:
 bottom otter trawl (OTB), pelagic pair trawl (PTM), beam trawl (TBB), 
 purse seine (PS), and "other" fishing (OTHER, including dredges and 
 passive gears).

<p>

In this repository we release also:

  - a small subset of AIS signals broadcasted by vessels contained in the validated dataset (.csv);
  - all the parameters required to process the data, such as the input parameters needed to 
  classify fishing trips (.csv) and the trained Random Forest model (.rds) used to finally 
  assign the gear on a monthly basis and finalized to work in the Adriatic Sea
  - additional spatial layers required by the data processing (.shp).

<p>

A summary description of these data is provided in the Release notes. <br>

Please cite as:
<p>
ENA, & MAPS-MArine sPatial reSearch. (2021, May 14). MAPSirbim/AIS_data_processing: R4AIS (Version v1.0.1). Zenodo. http://doi.org/10.5281/zenodo.4761368

<p>

[![DOI](https://zenodo.org/badge/362045294.svg)](https://zenodo.org/badge/latestdoi/362045294)


# References

<div id="refs" class="references">

<div id="ref-Galdelli2018">

Liaw, Andy, and Matthew Wiener. 2018. “Package ’randomForest’. Breiman
and Cutler’s Random Forests for Classification and Regressionage
randomForest.”
<https://cran.r-project.org/web/packages/randomForest/index.html>.

</div>

</div>



