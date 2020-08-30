# Ford GoBike System Data Of The Year 2019
## by Osama Alqahtani


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

### Dataset source:
> From : https://www.lyft.com/bikes/bay-wheels/system-data
And the first four months from this one: https://s3.amazonaws.com/fordgobike-data/index.html
becuase the previous link has updated data sets which doesnt contain members informations.

### Wrangling Process:
> In the process of wrangling the dataset, I dropped some of the unuseful columns in my analyzing and I added some columns that will help me in my explorations which were: trip duration in minutes which I calculated from the trip duration in seconds column, and trips' start month which I got from the start time column, and members age which I calculated it from members birth year column.


## Summary of Findings

> After exploring the dataset I found out that weather doesn't affect the trip durations and also the trip duration doesn't depend on gender nor age.


## Resources

> I used two sites that helped me in plotting:
https://seaborn.pydata.org/index.html
https://python-graph-gallery.com