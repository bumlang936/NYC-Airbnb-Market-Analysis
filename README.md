# **NYC Airbnb Market Analysis Final Poster:** 

### Background and Overview:

- Hosts, travelers and analysts can’t see price patterns across thousands of New York City Airbnb listings.
- Where are the priciest and cheapest listings? How do boroughs compare? Where is availability longest?
- Tools: R (ggplot2, dplyr, sf) for the charts and Adobe Illustrator for the poster layout.

### Data Structure Overview:

- Used "New York City Airbnb Open Data" on Kaggle.
- There are 48,895 listings and 16 columns.
- **Key columns:** price, borough, neighborhood, room type, minimum nights, number of reviews, location coordinates, and days available per year.
- Price capped at $500 on the maps so outliers don’t wash out the color scale.

### Executive Summary:

Location and room type drive price. Manhattan averages about $197 a night versus $88 in the Bronx, and an entire home averages about $212 versus $70 for a shared room.

### Insights Deep Dive:

Borough averages: Manhattan $197, Brooklyn $124, Staten Island $115, Queens $100, Bronx $88.
Room type averages: entire home $212, private room $90, shared room $70, so room type creates the bigger gap.
Most listings fall below roughly $200, with a long tail of luxury listings pulling averages up.

### Recommendations:

Hosts: benchmark rates by borough and room type.
Travelers: weigh what location versus room type adds to cost.
Next steps: add medians, finish the availability analysis, confirm the Bronx appears on both maps, and rebuild as an interactive dashboard.
