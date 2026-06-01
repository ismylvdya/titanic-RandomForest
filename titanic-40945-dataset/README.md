# OpenML dataset: Titanic

https://www.openml.org/d/40945

## Structure

The dataset has the following file structure:

* `dataset/`
  * `tables/`
    * [`data.csv`](dataset/tables/data.csv): CSV file with data
    * [`data.pq`](dataset/tables/data.pq): Parquet file with data
  * [`metadata.json`](dataset/metadata.json): OpenML description of the dataset
  * [`features.json`](dataset/features.json): OpenML description of table columns
  * [`qualities.json`](dataset/qualities.json): OpenML qualities (meta-features)

## Description

**Author**: Frank E. Harrell Jr., Thomas Cason  
**Source**: [Vanderbilt Biostatistics](http://biostat.mc.vanderbilt.edu/wiki/pub/Main/DataSets/titanic.html)  
**Please cite**:   

The original Titanic dataset, describing the survival status of individual passengers on the Titanic. The titanic data does not contain information from the crew, but it does contain actual ages of half of the passengers. The principal source for data about Titanic passengers is the Encyclopedia Titanica. The datasets used here were begun by a variety of researchers. One of the original sources is Eaton & Haas (1994) Titanic: Triumph and Tragedy, Patrick Stephens Ltd, which includes a passenger list created by many researchers and edited by Michael A. Findlay.

Thomas Cason of UVa has greatly updated and improved the titanic data frame using the Encyclopedia Titanica and created the dataset here. Some duplicate passengers have been dropped, many errors corrected, many missing ages filled in, and new variables created. 

For more information about how this dataset was constructed:
http://biostat.mc.vanderbilt.edu/wiki/pub/Main/DataSets/titanic3info.txt


### Attribute information  

The variables on our extracted dataset are pclass, survived, name, age, embarked, home.dest, room, ticket, boat, and sex. pclass refers to passenger class (1st, 2nd, 3rd), and is a proxy for socio-economic class. Age is in years, and some infants had fractional values. The titanic2 data frame has no missing data and includes records for the crew, but age is dichotomized at adult vs. child. These data were obtained from Robert Dawson, Saint Mary's University, E-mail. The variables are pclass, age, sex, survived. These data frames are useful for demonstrating many of the functions in Hmisc as well as demonstrating binary logistic regression analysis using the Design library. For more details and references see Simonoff, Jeffrey S (1997): The "unusual episode" and a second statistics course. J Statistics Education, Vol. 5 No. 1.

## Contributing

This is a [read-only mirror](https://gitlab.com/data/d/openml/40945) of an [OpenML dataset](https://www.openml.org/d/40945). Contribute any changes to the dataset there. Alternatively, [fork the dataset](https://gitlab.com/data/d/openml/40945/-/forks/new) or [find an existing fork](https://gitlab.com/data/d/openml/40945/-/forks) to contribute to.

You can use [issues](https://gitlab.com/data/d/openml/40945/-/issues) to discuss the dataset and any issues.

For more information see [https://datagit.org/](https://datagit.org/).

