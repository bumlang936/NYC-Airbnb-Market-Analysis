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

**Borough Averages:** 
- Manhattan = $197
- Brooklyn = $124
- Staten Island = $115
- Queens = $100
- Bronx = $88
  
**Room Type Averages:** 
- Entire home = $212
- Private room = $90
- Shared room = $70

**Key Observations:**
- Room type creates a bigger gap in average price.
- Most listings fall below roughly $200.
- Has a long tail of luxury listings which increase the average price.

### 5. Recommendations:

- **Hosts:** should price against listings in the same borough and room type, not the citywide average.
- **Travelers:** a private room averages less than half the price of an entire home, so room type can save more than location.
- **Analysts:** use the maps to pick neighborhoods that deserve a closer look and look for potential outliers and developing trends.
- **Next steps:** add other visuals like a box plot to show the range of prices, confirm the geospatial coding of New York City looks accurate, and rebuild as an interactive dashboard.
