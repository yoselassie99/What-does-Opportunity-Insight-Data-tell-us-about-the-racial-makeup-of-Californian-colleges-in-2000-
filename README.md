# What does Opportunity Insight Data tell us about the racial makeup of Californian colleges in 2000?

## Background
The issue of race and college admittance has been a controversial topic for years. Colleges for years have placed emphasis on creating a more diverse and inclusive community that encourages ecclectic and motivated thinkers. While this is somewhat of an uncontroversial approach to education, concerns on racial quotas and affirmative action force individuals to question whether college admittance is purely merit based or partially motivated by ethnic background. This is an argument frequently used when a highly accomplished student is not accepted to the university of his/her dream. While some fear colleges are becoming more focused on diversity than achievements, others believe colleges have a long way until achieving educational equity. 

This project will investigate the racial makeup of four year colleges and university in California from the year 2000. In investigating racial makeup, we want to analyze the state of California's population share per demographic as well as which direction specific universities are deviating from the state's averages. 

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

"Other", which we can assume is predominantely Caucassian, have the largest population share at 4 year universities in California (60.6%). The other four groups (Asian/Pacific, Black, Hispanic and "Alien") represent the rest of California's pollution share. Interstingly, Asian/Pacific, Black and "Alien" have relatively high SD values for their respective means. This indicates some universities are making larger strides than others in diversifying their student population than others.

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
Woodbury College has high Black, Hispanic and "Alien" population shares, with Hispanic and Alien specifically having population shares over 1 SD above the average. "Other" population share is over 1 SD below the state average. 


## Summary and Notes 
- The five anchors show various deviations from the mean. However, Woodbury College (with three different groups over 1 SD away from the mean) shows the most deviation.
- Pomona has the least diversity in terms of demographic shares, as Asian/Pacific, Black, Hispanic and "Alien" are all below respective averages while "Other" is above state average. 
- Small averages accompanied by large standard deviations indicate although some universities are trying to diversify their student bodies, others have significant progress to make. 
It is important to note that inclusion of large public universities like UCLA and UC Berkeley may skew the data to a degree as their student body is significantly larger than small liberal arts universities. 
