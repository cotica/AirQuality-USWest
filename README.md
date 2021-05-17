# Wildfires and Air Quality

## Problem
</br>

Our research seeks to understand the relationship between wildfires and their impact on air quality. Namely, we are looking to identify whether a strong relationship exists between those factors, analyzing individual variables including NO2, AQI and others.

<p align=center>
<img src="./assets/orange_sky_sf.png" width=500 alt="San Francisco covered in smoke from California wildfires" title="San Francisco covered in smoke from California wildfires">
</p>


</br>

## Team

Veronica Antonova (CA) [LinkedIn](http://linkedin.com/in/vstepanova) | [GitHub](https://github.com/cotica)

Helen Meigs (HI) [LinkedIn](https://www.linkedin.com/in/helenbm/) | [GitHub](https://github.com/welcometohelen)

Riley Robertson (WA) [LinkedIn](https://www.linkedin.com/in/riley-d-robertson/) | [GitHub](https://github.com/rileydr)

</br></br>
## Data sources

All data cover the period of 2012 or later.

* [`Fire Data`](https://frap.fire.ca.gov/frap-projects/fire-perimeters/)
* [`Pollution data`](https://www.kaggle.com/sogun3/uspollution)
* [`Air Quality`](https://docs.airnowapi.org/files)
<!---* [CA EV purchases]()--->

</br></br>

## Important terminology

* `AQI` refers to the air quality index and is measured from Good (Green) to Hazardous (Purple).

* `NO2` refers to ozone emission.

* A `prescribed fire` is a planned fire.


## Data acquisition and wrangling

Data were scraped from the air quality site. Additional data were acquired from a researcher in Berkeley as well as several Kaggle datasets.

All data were cleaned, scaled as appropriate and merged for processing and modeling.

Nulls were imputed where necessary.


</br></br>
## Data exploration

We have sought to understand some the following:

* Is there a direct relationship between AQI and fires?

* What fire trends can be observed over the years?

* Is there a cyclical relationship we can identify between smoke, fire and air quality?
 

_Insert map of fires here_

## Modeling techniques

</br></br>
## Key findings

* 94% of all fires are wildfires (rest are prescribed)
* California dominates both wildfire frequency and the pollution charts
* The vast majority (70%) of fires have a smoke score of just 1
![](./assets/fires_by_score.jpg)
* There seems to be no relationship between the smoke score and the acreage of fire's impact (burn)
* The most massive fires, by burn acreage, in our dataset are in 2012 and 2013
![](./assets/fire_by_acreage.jpg)

</br></br>
## Recommendations and conclusions

Many factors influence air quality (_[source](https://docs.google.com/document/d/11ob6Qt6jiWdM_G-ge4UOWN0kTx-5hHZep2QBnOp1yjY/edit?usp=sharing)_). We sought to analyze a few of these, seeking to understand the relationship between what we predicted to be the strongest factors. In doing so, we acknowledge that we have left off many potential influencers on this equation, including but not limited to atmospheric conditions (wind patterns, presence of a drought), geographic topography, climate changes, and even behavioral changes (including adoption of electric vehicles and their eventual impact on the reduction of emissions). It would be ambitious to study all these factors in a short time frame, but this project could benefit from future iterations that can include these analyses.


</br></br>
## Python Notebooks and Presentation Links

* [`EDA`](./code/va-EDA.ipynb)
<!---
* [Main notebook report with findings]()
* [Scraping notebook]()
* [Modeling notebook]()
--->
* [`Slides`](https://docs.google.com/presentation/d/10I3ZuSoi1APt5GTSe4lJPC51fLsKmMWfKAVmRrd-5NY/edit#slide=id.p)

<!---
<div style='float: center; padding=50px'>
<img src='https://github.com/rileydr/AirQuality-USWest/blob/main/assets/repository_banner_dark.png'>
</div>
--->
</br></br>
