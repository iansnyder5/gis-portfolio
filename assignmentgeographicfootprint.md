# Assignment: Creating your own geographic footprint

## Option 1: Investigate the provided sample dataset

I have not been tracking my own data via Google Takeout, so I planned to used the provided sample data. Unfortunately, I could not get the JSON --> python --> csv process to work, so I imported the provided csv file for when all else goes wrong (because it did).

I created a point feature from the csv file, which contained a data/time feature, latitude, and longitude. The points are in and around Paris, France.

### Where you live, work, etc. 

Because the data contain date/time properties, I adjusted the "Time" property in the contents menu to reflect the points' date/time data. I was then able to play the sequence between 8/15/2018 and 8/30/2018 and follow the points through time. It appears that the "home" location is within the city of Paris, as the points returned to Paris after traveling elsewhere each time. The sample "subject" may also work in Paris, but they appear to travel frequently, which could be for work or pleasure.

### When you visited a place

The subject appeared to take most trips for a day. One trip appeared to be overnight, as the curve which the points formed was consistent on consecutive days. The points related to that trip would end at a spot and then overlap the points from earlier that day on the return trip. I could discover the rough destination from the point at which the subject appeared to "turn around."

### How long you stayed

I watched the data through time day-by-day. If the pattern and location of the points changed between days, it is likely that the subject only stayed in their location for that given day. This was the case for most of the subject's trips. There were multiple strings of consecutive days in which the points clustered in Paris, when the subject must have stayed in and around their home.

### How you got there

The points, when traveling outside Paris, appear to follow a consistent curve that aligns with major roads in the basemap, which makes me think that the subject mostly travels by car. For those few chains of points that don't align with major highways, I would think the subject traveled by rail.

### Where you went next

It is easier to tell where the subject went next when slowing down the progression of time to half-days or slower. However, even without this adjustment, because the points play in sequence by day, I can tell what general area the subject ended up in in one day and started the next.

### Places you visit repeatedly or frequently

This is most obvious without the time feature. I attempted to create a kernel density map to look at this aspect more clearly but could not get the density map to plot. It is evident enough with the eye alone, when Time is turned off, to tell that there is a larger cluster of points in and around the city of Paris. The points and chains of points are more sparse in outerlying regions.

### What you were likely doing at the time

If I had a better knowledge of France, I would probably be able to deduce what the subject was doing in each region and on each day. I assume that most trips within France were for day-to-day errands and likely office work, and I would think that most trips to the outerlying places involved business or pleasure.

## Takeaways

I found it rather easy to analyze the data as described. The points came with a date/time feature, and I did not have to perform any spatial analysis other than activating and analyzing this feature. From a policy standpoint, this is mildly terrifying. I'm a second-year graduate student, and I could use these (and more of similar) data to target advertising, to shape policy programs, and to survey residents. Consumers still lack a lot of information about how their data are used, and Congress still hasn't regulated many of the things for which industry uses our data. This really solidified, for me, how much information we can divulge about ourselves if we aren't intentional and careful.
