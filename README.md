# 5CollegeDatafest
## Programmed in R in RStudio

##Worked in a team of 3 at a data science hackathlon

## Involved Canadian National Women's Rugby Team Dataset

# *Disclaimer* cannot post csv file due to Canadian National Women's Rugby Team Organization request the data to be not public

Variables:
SleepHours
Fatigue
Desire
ObjectiveRating
FocusRating
Nutrition
SessionType
etc.

# Objective: Find value in the data to see what causes fatigue in the athletes

## Data Visualization

In order to see what my team was dealing with and see what parts of the data we can analyze, we boxplotted SleepHours, Fatigue, Soreness, and Desire.
From this my team was able to see the coorelation between fatigue and sleep, motivation of the players.

## Statistcal Modeling (Multi-Linear Regression)

I independently programmed a muli-linear regression on the data with the fatigue variable (Fatigue) as the dependent variable.

Indepedent Variables chosen:
Desire: 1 to 5 scale, 5 being the highest, motivation to play and get better
SleepQuality: 1 to 5 scale, 5 being the highest
Nutrition: 1 to 5 scale, 5 being the highest
Menstruation: 0 = no menstration, 1 = menstruation
SessionType: Type of Training Involved - Combat, Conditioning, Game, Mobility/Recovery, Skills, Speed, Strength
DailyLoad: estimated value of "load" per day (lbs)

## Result

SleepQuality and Desire the only variables that reduced fatigue in the athletes.
Certain SessionType activities actually increase fatigue levels.
