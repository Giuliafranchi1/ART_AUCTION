# Exploring Art Market Dynamics
This repository contains code and analysis for my research project focused on understanding the determinants of final art prices. Through data analysis and modeling, I investigate various factors that influence the prices of artworks, shedding light on the intricate dynamics of the art market.

## DATASET N.1: CHRISTIE'S AUCTION HOUSE
This dataset, sourced from [Christie's auction house](https://github.com/georgiecoetzer/What-Makes-Art-Valuable/tree/main), encompasses records from 2012 to 2022, detailing approximately 1,187 artworks. Data was gathered using Selenium for web scraping. The dataset emphasizes artist characteristics and artwork details.

### Key Variables:
- Artist: Artist's name and lifespan.
- Art Title & DoC: Title and creation date of the artwork.
- Price & Estimates: Sold price, with low and high estimates.
- Auction Details: Auction title, closing date, and accuracy of price estimates.
- Artwork Details: Dimensions and currency (typically USD).
- Artist Metrics: Age, alive status, and popularity.


For more details, check out the [Medium article](https://medium.com/@gcoetzer/what-makes-art-valuable-data-scraping-and-exploratory-data-visualizations-82966b218a07).


## DATASET N.2: ARTWORK PHYSICAL ATTRIBUTES 
This dataset, sourced from a [GitHub repository](https://github.com/jasonshi10/art_auction_valuation/tree/master), provides detailed information about artworks auctioned off. It encompasses a total of 41,253 entries, each representing an individual piece of art, spanning a time period from May 13, 1985, to December 4, 2014. It offers a deep dive into these tangible attributes, providing a comprehensive set of features that describe the physical characteristics of artworks.

### Basic Details
- Information about the artist, including their name, country of origin, year of birth, and year of death. For instance, an artwork by “Pablo Picasso” from “Spain” is included in the dataset.
### Artwork Specifies
- Details about the artwork itself, such as its name, the material used (e.g., “Oil on canvas”), and its dimensions (e.g., 24 inches in height and 12 inches in width).
### Visual Attributes
- This dataset delves deep into the visual characteristics of the pieces, capturing features like the dominant color, brightness levels, unique color ratios, and percentages of high and low brightness. For example, an artwork might have a dominant color of "Green" with a mean brightness value of "129".
### Advanced Image Analysis
- Leveraging advanced image processing techniques, the dataset provides insights into the percentage of edges and corners in the artwork, detected using the Canny Edge Detection and Harris Corner Detection algorithms, respectively. Additionally, it counts the number of faces present in the artwork's imagery.
### Auction Details
- Information about when the artwork was sold at auction, such as “2007-05-03”.

The artworks in this dataset appear to have been sold across various auction houses, rather than being confined to a single entity. This broader scope offers a more diversified perspective on the art market dynamics. For a more detailed insight into how the data was acquired and processed, please refer to the following [GitHub link](https://github.com/ahmedhosny/theGreenCanvas/blob/gh-pages/ImageProcessing1210.ipynb).
