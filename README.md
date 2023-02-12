# Elections and Media

#### This repository contains the files to explore two ideas: i) how media consumption evolves as elections approach, and ii) how proximity to elections affects people’s opinions on the state of the country. This is a work in progress, at present date mostly focuses on studying the first point. 

#### **The Elections-and-Media folder contains four folders:**
1. NDI - contains a notebook file ("ndi_parser") that must be run as such, that retrieves election dates data from the National Democratic Institute between 2006 and 2022, and builds a dataset ("election_dates").
2. Wiki elections parser - contains a notebook file ("wiki_elections_parser") that must be done as such, that retrieves election dates data from Wikipedia for 2013, 2015, 2016, 2017, and 2018, and builds a dataset ("election_dates_wiki").
3. Elections and surveys - contains a notebook file ("Election_dataset") that must be run as such, that puts together the previously retrieved data and the Afrobarometer surveys. It then shows a first step towards the visualization of the output. 
4. Afrobarometer - contains rounds 2 through 7 of the csv files downloaded from the Afrobarometer website.

The order in which the files must be run is the following: i) ndi_parser, ii) wiki_elections_parse, and iii) Election_dataset.