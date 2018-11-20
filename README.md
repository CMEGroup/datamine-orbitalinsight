# Datamine Orbital Insight




This project introduces a potential use of Orbital Insight data.  Orbital Insight provides global and regional crude oil volume estimates, monitoring over 5 Billion barrels of oil storage capacity across more than 25,000 tanks.  

Further information about Orbital Insight and Datamine can be found at CME Group [CME Datamine Orbital Insight](https://www.cmegroup.com/market-data/orbital-insight.html "CME Datamine RS Metrics Data") and [Orbital Insight Information](https://orbitalinsight.com/ "Orbital Insight Homepage")

![Orbital Insight Crude Oil Volume Estimate](https://github.com/CMEGroup/datamine-orbitalinsight/blob/master/image/OrbitalInsightGraph.JPG)


## Run on Binder
Automatically run this in a hosted Jupyter Notebook with all the dependencies.  
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/CMEGroup/datamine-orbitalinsight/master)


## To Run This Analysis Locally

To use the examples in Juptyer Notebook from Anaconda Python.  The following will clone this repo, including an environment.yml file that will create the proper Anaconda environment with all the dependencies.  Next you can launch the Jupyter Lab environment.  

```
git clone https://github.com/CMEGroup/datamine-orbitalinsight.git
cd datamine-orbitalinsight
conda env create
source activate  datamine-orbitalinsight
jupyter notebook


```
Alternatively, you can use your own python environment but review the environment.yml file to determine package dependencies.

## Notebook Summary

There is a notebook for data introduction and analysis.  General summary of the notebook is below.

### Orbital Insight Blog
[CME Datamine Orbital Insight Data Analysis](https://github.com/CMEGroup/datamine-orbitalinsight/blob/master/Orbital%20Insight%20-%20Analysis.ipynb "Orbital Insight Analysis")

This analysis introduces Orbital Insight data and finds a potential relationship between Orbital Insight data and CME crude oil futures data.




## Data Supplied
This workbook leverages altered data in the analysis. It displays the general statistical 
properties of the original data set.

## Author
[Seo Wook Jang](https://github.com/sjangcme) - CME Group Global Data Licensing Services

## Questions and Comments?
Please contact markettechsales@cmegroup.com or use the Issues feature.

## Notice
The information herein has been complied by CME Group for general informational and education purposes only and does not constitute trading advice or the solicitation of purchases or sale of futures, options, or swaps. The views in this video reflect solely those of the author and not necessarily those of CME Group or its affiliated institutions. All examples discussed are hypothetical situations, used for explanation purposes only, and should not be considered investment advice of the results of actual market experience. Although every attempt has been made to ensure the accuracy of the information herein, CME Group and its affiliates assume no responsibility for any errors or omissions. All data is sourced by CME Group unless otherwise stated. All matters pertaining to rules and specification herein are made subject to and are superseded by official CME, CBOT, NYMEX, and COMEX rules. Current rules should be consulted in all cases concerning contact specifications.
 
CME Group, the Globe Logo, CME, Globex, E-Mini, CME Direct, CME Datamine and Chicago Mercantile Exchange are trademarks of Chicago Mercantile Exchange Inc.  CBOT is a trademark of the Board of Trade of the City of Chicago, Inc.  NYMEX is a trademark of New York Mercantile Exchange, Inc.  COMEX is a trademark of Commodity Exchange, Inc. All other trademarks are the property of their respective owners.
