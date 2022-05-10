## Finding the optimal location for a fitness center in Aarhus

### Contribution

Sofie Thinggaard au613703

201909063@post.au.dk

## Structure

## Datasets made in the markdown file

load("data/data_gym.rda") #OSM fitness center data without NAs and duplicates and flipped long lat coordinates + the parishes it is located in + additional found fitness centers

load("data/data_sogn.rda") #number of fitness center in each parish and how many in the target group lives there

load("data/aarhus_mun.rda") #parishes in Aarhus municipality (for the boarders of the map)

load("data/target_gym_parish.rda") #the number of target group per fitness center in the parish

## Files to load

Fitness_extra.csv #additional fitness centers found from https://www.facilitetsdatabasen.dk/

sogn.xlsx #how many of the target group (women between 20-39 years old) that lives in the various parishes in Aarhus municipality from https://www.statbank.dk/statbank5a/SelectVarVal/Define.asp?Maintable=KM5&PLanguage=0

two files from Github: https://github.com/sebastianbarfort/mapDK/tree/master/data?fbclid=IwAR0S7aB9PMYNQFZXHuHLn-qQQRYed2sdA4LVFoGUQ-v2s0oXb6VEIuI-j8s

parish.rda #the parish boarder coordinates for all parishes in Denmark

municipality.rda #the municipality boarder coordinates for all municipalities in Denmark
