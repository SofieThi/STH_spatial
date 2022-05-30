## Finding the optimal location for a fitness center in Aarhus

### Contribution

Sofie Thinggaard au613703

201909063@post.au.dk

## Structure

This repository has the following directory structure:

| Column | Description|
|--------|:-----------|
```datasets_made```| the various datasets made in the rmd
```load``` | files to load in order to run the code
```output``` | the final map showing the top three optimal locations in Aarhus for a gym with women (20-39) as target group
```STH_fitness_center.Rmd``` | the code in rmd
```Fitness_html.html``` | the code in html. The final map in html format is rendered wrong, see output folder


## Usage (reproducing results)

In order to run this code, clone the repository and load the data from the "load" folder into the R space. The code is called: STH_fitness_center.Rmd

## Datasets made in the markdown file (see "datasets_made" folder)

load("data/data_gym.rda") = OSM fitness center data without NAs and duplicates and flipped long lat coordinates + the parishes it is located in + additional found fitness centers

load("data/data_sogn.rda") = number of fitness center in each parish and how many in the target group (women aged 20-39) lives there

load("data/aarhus_mun.rda") = parishes ONLY in Aarhus municipality (for the parish boarders of the map)

load("data/target_gym_parish.rda") = the number of target group (women aged 20-39) per fitness center in the parish

## Files to load (see "load" folder)

-Fitness_extra.csv = additional fitness centers found from https://www.facilitetsdatabasen.dk/

-sogn_fin.xlsx = how many of the target group (women between 20-39 years old) that lives in the various parishes in Aarhus municipality from https://www.statbank.dk/statbank5a/SelectVarVal/Define.asp?Maintable=KM5&PLanguage=0

-two files from Github: https://github.com/sebastianbarfort/mapDK/tree/master/data?fbclid=IwAR0S7aB9PMYNQFZXHuHLn-qQQRYed2sdA4LVFoGUQ-v2s0oXb6VEIuI-j8s

parish.rda = the parish boarder coordinates for all parishes in Denmark

municipality.rda = the municipality boarder coordinates for all municipalities in Denmark


## Link to repository on Github

https://github.com/SofieThi/STH_spatial 
