# What this is

This is a script which takes in data from MIT on the U.S. House Election results for a given year and compares it to demographic data from the U.S. Census' community survey of the same year.

This script then outputs a set of eight plots to show the relationship between the two and the significance of it. This fit line is drawn with single linear regression however the significance level is calculated using a multiple linear regression model with all eight variables. There aren't really any crazy conclusions to draw from this that haven't been shown a hundred times elsewhere, but it was a fun project and it was nice to learn about how to access census and elections data. In the future, if I have more ideas, I may return to this and try to show some more interesting results.

Outputs for the years 2008-2020 can be seen in the *Plots* folder. Unfortunately the census changes the names of the variables for the community survey every so often, so I was unable to generalize the code to work for more years. There's probably a way to do it with more time input, but I just manually checked the names and set them for the years I chose.

I also wanted to try using the Python library *cenpy*, but I had already completed most of the project by the time I found out about it, and found that my code was able to more easily do the specific thing I wanted than to try to figure out how to do a similar thing with cenpy. In the future, that's also an area I'd love to look into further.
