# **NYC Airbnb Market Analysis Final Poster:** 

### 1. Background and Overview:

- Hosts, travelers and analysts can’t see price patterns across thousands of New York City Airbnb listings.
- Where are the priciest and cheapest listings? How do boroughs compare? Where is availability longest?
- **Tools:** R (ggplot2, dplyr, sf) for the charts and Adobe Illustrator for the poster layout.

### 2. Data Structure Overview:

- Used "New York City Airbnb Open Data" on Kaggle.
- There are 48,895 listings and 16 columns.
**Key columns:**
  - price
  - borough
  - neighborhood
  - room type
  - minimum nights
  - number of reviews
  - location coordinates
  - days available per year
- Price capped at $500 on the maps so outliers don’t wash out the color scale.

### 3. Executive Summary:

- Location and room type drive price.
- Manhattan averages about $197 a night versus $88 in the Bronx.
- An entire home averages about $212 versus $70 for a shared room.

### 4. Insights Deep Dive:

**Borough averages:** 
- Manhattan = $197
- Brooklyn = $124
- Staten Island = $115
- Queens = $100
- Bronx = $88
  
**Room type averages:** 
- entire home = $212
- private room = $90
- shared room = $70
  
Room type creates a bigger gap in average price.
Most listings fall below roughly $200.
Has a long tail of luxury listings which increase the average price.

### 5. Recommendations:

Hosts: benchmark rates by borough and room type.
Travelers: weigh what location versus room type adds to cost.
Next steps: add medians, finish the availability analysis, confirm the Bronx appears on both maps, and rebuild as an interactive dashboard.
