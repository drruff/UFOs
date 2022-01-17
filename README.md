# UFOs

## Overview

Created a website that has data on UFO spottings, then created a dynamic table so that we can filter based on the various pieces of available data on these UFO spottings.

## Summary

- Created a website that allows users to see UFO findings in a table, with a filter section based on each columns data (except for comments):

![Base website](https://github.com/drruff/UFOs/blob/main/Examples/base.PNG)

- Made the table update automatically based on typed in response. The images below show it working: First picture demonstrating it can filter by city, second show the filter works on with multiple filters (which gives no results since there is nothing that meets the filters), the third shows filters updated when we removed one filter, and the last one just shows that multiple filters can give results if there are results.

![first pic](https://github.com/drruff/UFOs/blob/main/Examples/city%20filter.PNG)
![second pic](https://github.com/drruff/UFOs/blob/main/Examples/multiple%20filters%20neg.PNG)
![third pic](https://github.com/drruff/UFOs/blob/main/Examples/multiple%20filters%20pos.PNG)
![fourth pic](https://github.com/drruff/UFOs/blob/main/Examples/updates%20with%20removal.PNG)

## Results

- One major drawback of this filtering system is that the filter does not recognize a filter has been updated until user leaves the input box (either by tabbing, or clicking out of it) so things like typing and waiting or typing and pressing enter WILL not update the filter.
- Two things that can make the filter better would be: 
  - Making a range of data allowed (so like a range of dates, or multiple cities at once)
  - having a drop down menu for shapes (this category is a little ambiguous since options like "unknown" and "light" which are both clearly not literal shapes makes it hard to next to impossible to know all possible filters) since there is a small list of options for this category it would make more sense than a typed response. Could also be added to states and countries)
