## Autism and Vaccines: A Historical Analysis Using R and `ggplot2`

## Introduction:
Vaccines have helped save millions of lives. In the 19th century, before herd immunization was achieved through vaccination programs, deaths from infectious diseases, like smallpox and polio, were common. However, today, despite all the scientific evidence for their importance, vaccination programs have become somewhat controversial.

The controversy started with a [paper](http://www.thelancet.com/journals/lancet/article/PIIS0140-6736(97)11096-0/abstract) published in 1988 and lead by [Andrew Wakefield](https://en.wikipedia.org/wiki/Andrew_Wakefield) claiming there was a link between the administration of the measles, mumps and rubella (MMR) vaccine, and the appearance of autism and bowel disease. Despite much science contradicting this finding, sensationalists media reports and fear mongering from conspiracy theorists, led parts of the public to believe that vaccines were harmful. Some parents stopped vaccinating their children. This dangerous practice can be potentially disastrous given that the Center for Disease Control and Prevention (CDC) estimates that vaccinations will prevent more than 21 million hospitalizations and 732,000 deaths among children born in the last 20 years (see [Benefits from Immunization during the Vaccines for Children Program Era — United States, 1994-2013, MMWR](https://www.cdc.gov/mmwr/preview/mmwrhtml/mm6316a4.htm)). 

## Data:
The data used for these plots were collected, organized and distributed by the [Tycho Project](http://www.tycho.pitt.edu/). They include weekly reported counts data for seven diseases from 1928 to 2011, from all fifty states. The yearly totals can be found in the `dslabs` package:

## Acknowledgement:
The introduction and data were based on a class assignment from Harvard Chan's Introduction to Data Science Course.
