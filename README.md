# MUSA 508 Final Project: Wildfire Manager

**By**:
* Hui Tian, huitian@upenn.edu
* Jiali Yao, jialiyao@@upenn.edu

## Introduction

Due to the climate change and global warming, the environment and all living beings have suffered tremendously from wildfire, which becomes more frequent and severe in recent decade. Especially in California, over the years, rampant wildfires have plagued the state of California, creating economic and environmental loss. In 2018, wildfires claimed more than 100 lives in California, over 1.6 million acres of land has burned and caused large sums of environmental damage. Although the government have paid much attention to this issue, and many efforts have been made, the situation is not obviously changed. Last year (2020), there are still over 4.2 million acres of land has burned by around 10,000 fire incidents and more than 10,000 structures damage.

Currently, there are many applications and websites that provide the wildfire prediction, but little focus on the financial analysis. Without a broad and comprehensive evaluation of wildfire risks and risk mitigation strategies, it is difficult to allocate funding related to wildfires efficiently and effectively.

In this project, we built a logistic Regression model to predict probability occurrence rate of wildfires in part of North California and made it into an application for stakeholders. Model is validated across 100 folders and spatial patterns. At the end we have a cost-benefit analysis to optimize the threshold on which we can have the minimum cost. Features are integrated into the model as below:

- 5 years’ records of wildfire
- Weather (wind Direction, wind Speed, temperature, precipitation, humidity)
- Land Cover (forest, woodland, shrub, herbaceous, wetland, water)
- Terrain (elevation, slope, aspect)
- Wildlife urban interface (WUI)
- Powerline (Electric Transmission Line)

 With the result from the model, our app includes functions as below. For example:

- Predict high fire risk zones 
- Estimate the optimal cost & benefit
- Create fire hazard mapping
- Report potential risk on patrol


## Stakeholders

* California Department of Forestry and Fire Protection (CAL FIRE) 

## Presentation Video

https://youtu.be/A07PK3mmy34


## Data sources

- **Wildfire records** -- [FRAP](https://frap.fire.ca.gov/frap-projects/fire-perimeters/)
- **Weather** -- [riem]( Package in R to get the weather information)
- **Land Cover** -- [DATA_BASIN](https://databasin.org/galleries/07acc8fec40a41f586a421cdcef98e96/)
- **Terrain** -- [DATA_BASIN](https://databasin.org/datasets/78ac54fabd594db5a39f6629514752c0/)
- **Wildland Urban Interface** -- [FRAP](https://frap.fire.ca.gov/media/10633/wui12_3.zip)
- **Powerline** -- [CA_Government](https://gis.data.ca.gov/datasets/CAEnergy::california-electric-transmission-lines/about)


## Wireframes

![arch.diagram](https://github.com/Hui-Tian/Wildfire_Manager/blob/main/wildfire_manager_wireframe.jpg)
