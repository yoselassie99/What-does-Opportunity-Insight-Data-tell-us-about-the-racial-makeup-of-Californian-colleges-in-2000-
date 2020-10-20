# What does Opportunity Insight Data tell us about the racial makeup of Californian colleges in 2000?

## Background
The issue of race and college admittance has been a controversial topic for years. Colleges for years have placed emphasis on creating a more diverse and inclusive community that encourages ecclectic and motivated thinkers. While this is somewhat of an uncontroversial approach to education, concerns on racial quotas and affirmative action force individuals to question whether college admittance is purely merit based or partially motivated by ethnic background. This is typically the argument when a highly accomplished student is not accepted to the university of their dream. However, 

This project will investigate the racial makeup of four year colleges and university in California from the year 2000.  

## Business Question
What does Opportunity Insight Data tell us about the racial makeup of Californian colleges in 2000?

## Data Source
Data on racial composition in America college populations was collected through Opportunity Insight data.

(https://github.com/yoselassie99/What-does-Opportunity-Insight-Data-tell-us-about-the-racial-makeup-of-Californian-colleges-in-2000-/blob/main/Opportunity%20Insights%20Raw%20Data.xlsx)

From there, data was filtered to remove non-CA and non-four year institutions. Colleges were also removed if they did not include data on one or more racial group. "Other" is considered mostly Caucassian but have the potential to include Native Americans as well due to the ambiguity. The other demographics and their respective z-score titles include:

- Asian or Pacific (z_asian_or_pacific)

- African American (z_black)

- Latino/Hispanic (z_hisp)

- "Alien" or Non-United States citizen (z_alien)


## Data Answer
The five corrected anchors paint different pictures on the racial make-up of their respective commmunities. Respective z-scores are relative to the state average to determine whether a certain racial demographic is considered high or low.

### Table 1: State Average for Racial Groups and Standard Deviation
![alt_text](https://github.com/yoselassie99/What-does-Opportunity-Insight-Data-tell-us-about-the-racial-makeup-of-Californian-colleges-in-2000-/blob/main/State%20Average%20and%20Standard%20Deviation.png)


### Table 2: Z-Scores for Corrected Anchors
![alt text](https://github.com/yoselassie99/What-does-Opportunity-Insight-Data-tell-us-about-the-racial-makeup-of-Californian-colleges-in-2000-/blob/main/Correct%20anchor.png)

#### Anchor 1
University of San Francisco has a high "alien" or non-US citizen share as well as low Hispanic share. Asian/Pacific population share is relatively high while Black population share is close to state average. 

#### Anchor 2
Pomona College has a low Hispanic and "alien" share while having a high "other" share. "Other" population share is also higher than state average. 

#### Anchor 3
Mount St. Mary's College has a high Black population share, high Hispanic share, low "alien" share and low "other" share. "Other" specifically has a population share nearly 2 SD below the state average. Asian/Pacific population share is close to state average. 

#### Anchor 4
San Jose State University has an extremely high Asian/Pacific population share as well as a low "other" share. Hispanic and "alien" population shares are close to the state average. 

#### Anchor 5
Woodbury College has high Black, Hispanic and "Alien" population shares, with Hispanic and Alien specifically having population shares over 1 SD above the average. 
