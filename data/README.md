# Dimensions 

Our data set contains immunization rate data for schools across the US. In the data set, there are 16 variables and 66,113 observations. For the variables, the data set displays characteristics of schools (index ID, state, year, name, school type, city, county, district, enrollment, MMR vaccination rate, school’s overall vaccination rate, percentage of students exempted from vaccination for religious reasons, percentage of students exempted from vaccination for medical reasons, percentage of students exempted from vaccination for personal reasons, school latitude, and school longitude). Each observation in the data set is a school in the US.

# Codebook 

`mmr`: Schools' Measles, Mumps, and Rubella vaccination rate. Note: Some of the `mmr` values are -1, signifying a lack of a valid data point. Thus, we filtered these out of our analyses so that our data would not be skewed. 

`region`: US region that each school's state belongs to, as defined by the US Embassy and Consulate in the Republic of Korea.**

`type`: Whether a school is public, private, or charter.

`party`: Political party affiliation of each school's state, as defined by how the state voted in the majority of the past 5 elections (not including the 2020 election).**

`exemptions`: Whether or not each school's state offers both religious and personal exemptions, as given by the Pew Research Center as of June 28, 2019.**

**Not in the original Wall Street Journal data set.