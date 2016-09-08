# Analysis of "Unfounded" Rape Reports

This repository contains data, code, and methodologies supporting the September 8, 2016 BuzzFeed News article, ["When Detectives Dismiss Rape Reports Before Investigating Them."](https://www.buzzfeed.com/alexcampbell/unfounded)

## Data Sources

The data in this analysis come from two main sources, described below.

### FBI Uniform Crime Reports

The FBI's Uniform Crime Report database tracks the number of crimes reported by most law enforcement agencies in the country. BuzzFeed News obtained UCR data, via the National Archive of Criminal Justice Data, for 2009 through 2014 (the most recent year available).

- 2009: http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/30766
- 2010: http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/33526
- 2011: http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/34586
- 2012: http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/35021
- 2013: http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/36122
- 2014: http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/36391

These data files are available in the `data/ucr` folder, zipped into `ucr-data.zip`.

Note: In 2013 the FBI [updated its definition of rape for the Uniform Crime Reports](https://ucr.fbi.gov/crime-in-the-u.s/2013/crime-in-the-u.s.-2013/rape-addendum/rape_addendum_final). It does not appear to have changed the overall rate of rape cases declared to be "unfounded."

### DOJ "Crosswalk" Table

The Bureau of Justice Statistics provides a ["crosswalk" file](http://www.icpsr.umich.edu/icpsrweb/NACJD/studies/35158), which connects the UCR's agency IDs to agency names and locations. 

## Analyses

- __Passage__: "In Scottsdale, Arizona, for example, 46% of rape reports were ruled unfounded between 2009 and 2014. In Oxnard, California, more than half of all rape allegations were classified as untrue. In Pittsburgh, the number is 30%. And in Baltimore County, it’s 34%."
- __Analysis__: See first table in the **Agencies With A High Percentage Of "Unfounded" Rape Reports** section of the [analysis notebook](https://github.com/BuzzFeedNews/2016-09-ucr-analysis/blob/master/notebooks/2016-09-ucr-analysis.ipynb).

---

- __Passage__: "In fact, the national average for unfounded rapes among police departments nationwide is 7%."
- __Analysis__: See section titled **National Percentage Of "Unfounded" Cases By Year** in the [analysis notebook](https://github.com/BuzzFeedNews/2016-09-ucr-analysis/blob/master/notebooks/2016-09-ucr-analysis.ipynb).

---

- __Passage__: "In response, the city changed its policies and hired a new commander to oversee how rapes were investigated. Its unfounded rate dropped precipitously, to below the national average."
- __Analysis__: See section titled **A Look At The Baltimore City Police Department** in the [analysis notebook](https://github.com/BuzzFeedNews/2016-09-ucr-analysis/blob/master/notebooks/2016-09-ucr-analysis.ipynb).

---

- __Passage__: "But, just next door, Baltimore County’s rate remained high, the highest in the nation for a police department of its size."
- __Analysis__: See section titled **A Look At The Baltimore County Police Department** in the [analysis notebook](https://github.com/BuzzFeedNews/2016-08-ucr-analysis/blob/master/notebooks/2016-08-ucr-analysis.ipynb) for a look at the Baltimore County Police Department's "unfounded" rate. See the second table in the **Agencies With A High Percentage Of "Unfounded" Rape Reports** section of the [analysis notebook](https://github.com/BuzzFeedNews/2016-09-ucr-analysis/blob/master/notebooks/2016-09-ucr-analysis.ipynb) for a comparison of the Baltimore County Police Department to all agencies that had at least 1,000 rape reports between 2009-14.

## Feedback

Contact John Templon at john.templon@buzzfeed.com or Alex Campbell at alex.campbell@buzzfeed.com.

Looking for more from BuzzFeed News? [Click here for a list of our open-sourced projects, data, and code.](https://github.com/BuzzFeedNews/everything)
