# N736 Fall 2017 - Lesson 12 - regression modeling

For this lesson we will be working with the HELP dataset. See more details on the HELP dataset at:

* [https://github.com/melindahiggins2000/N736Fall2017_HELPdataset](https://github.com/melindahiggins2000/N736Fall2017_HELPdataset)
* [https://melindahiggins2000.github.io/N736Fall2017_HELPdataset/](https://melindahiggins2000.github.io/N736Fall2017_HELPdataset/)

## Variables in HELP 

_{remember to review the HELP documentation}_

OUTCOME - For today's exercise, we will focus on the total score from the "Inventory of Drug Use Consequences", which is variable `indtot`.

Learn more about this survey tool at:

* [http://lib.adai.washington.edu/dbtw-wpd/exec/dbtwpub.dll?BU=http%3A//lib.adai.washington.edu/instrumentsearch.htm&TN=Instruments&CS=0&QY=find%20(AccessNo%20ct%20143)&RF=Full&DF=Full&MR=&NP=3&RL=0&DL=0&XC=&ID=&AC=QBE_QUERY](http://lib.adai.washington.edu/dbtw-wpd/exec/dbtwpub.dll?BU=http%3A//lib.adai.washington.edu/instrumentsearch.htm&TN=Instruments&CS=0&QY=find%20(AccessNo%20ct%20143)&RF=Full&DF=Full&MR=&NP=3&RL=0&DL=0&XC=&ID=&AC=QBE_QUERY)

CONTINUOUS "predictor" - for the simple linear regression we will use the CESD (depression) score, variable `cesd`.

GROUP/"Factor" - for the one-way ANOVA we will create 3 groups (low, moderate and high) from the PSS-fr (perceived social support from friends scale) using "cutpoints" defined by thirds (33rd and 67th percentiles), variable `pss_fr`.





