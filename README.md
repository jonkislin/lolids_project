# lolids_project
Project repository for Metis' Live Online: Intro to Data Science class, Fall 2017

UFO Data
### What data have been gathered?

The data (NUFORC ufo-reports) were gathered from planetsig's ufo-reports github
repository: https://github.com/planetsig/ufo-reports via command-line git.

### Data Exploration:
The dataset is messy. Very messy.
The first thing we've gotta do is take care of that index column. For some reason,
the index column is set as an inconsistently formatted date-time string.
First, we're going to want to tease that into its own column, and replace the index
column with a 0-indexed list.


### Questions to be asked:
Are there specific times and places when/where alleged UFO sightings were
attested to with more certainty?

Operationalized as:
Do certain keywords in the notes, such as "sure", "positively", "definitely",
"absolutely", "certain", etc. appear more often in certain geographical locations
and decades?

### Modeling Approaches
- Logistic regression
