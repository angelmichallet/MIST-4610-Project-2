# MIST-4610-Project-2

## Team Name

39217 Group 3	

## Team Members
Include information about the name of the team based on the team name assigned to the team on
ELC. Also include the names of all team members as well as links to their corresponding github
repos that have the project on them.
1. Angel Michallet [@angelmichallet](https://github.com/angelmichallet/MIST4610Project1)
2. Akhilesh Eloore [@akhileshe](https://github.com/akhileshe/MIST4610Group3Project1)
3. Rishi Patel [@rp65029](https://github.com/rp65029/MIST4610-Project-1)
4. Daniel Zavala-palafox [@dzavalapalafox](https://github.com/dzavalapalafox/Project1_MIST4610)
5. Penn Worden [@pennworden](https://github.com/pennworden/Group-Project)
6. Noah Martin [@noahhmartin03](https://github.com/noahhmartin03/MIST4610Project1)

## Description of Dataset
put description here


## Question 1 
**How have hate crime incidents of different bias types investigated by the police department changed over time in San Francisco?**
<img width="793" alt="image" src="https://github.com/angelmichallet/MIST-4610-Project-2/assets/130924513/2a20b13a-a58b-47f4-96df-8935f8568674">

**In light of the rise in racially biased hate crime incidents in 2021, how has the timing of this spike been during the COVID-19 pandemic specifically influenced the trends in racially biased hate crimes in San Francisco?**
<img width="797" alt="image" src="https://github.com/angelmichallet/MIST-4610-Project-2/assets/130924513/292f8690-2c26-4e74-ba61-c73abc2bcc5d">


## Question 2
**What is the distribution of different types of offense categories in hate crimes across various locations in San Francisco?**
<img width="1159" alt="image" src="https://github.com/angelmichallet/MIST-4610-Project-2/assets/130924513/537b892a-1c8c-40ac-97f1-12675619eed2">

**Given the significant number of hate crimes reported on highways and roads, what are the predominant types of hate crime biases (such as race, religion, sexual orientation) and types of offense acts observed in these specific locations?**
<img width="1174" alt="image" src="https://github.com/angelmichallet/MIST-4610-Project-2/assets/130924513/338e6c27-02e2-42db-9b7f-f742dc320eee">


## Manipulations Applied to the Dataset for Analysis
We did not need to apply any manipulations to the dataset itself, as our data meets the expectations of being quantifiable, measurable information that aligns with the standards of being meaningful and interpretable. Additionally, our dataset is free from duplicates, irrelevant or redundant entries, and any low-quality data. However, for relevance, we did need to apply filters on our data based on the focus of each of our graphs.

**Visualization #1 (Bias Types of Hate Crimes 2001-2023)**
- Filter on Most Serious Bias (The explicit bias motivation behind the most serious crime committed for the hate crime incident): Data was sorted to exclude Anti-Multiple Races (Group), Anti-Multiple Religions (Group), Anti-Other Christian, Anti-Other Race/Ethnicity/Ancestry, and Anti-Other Religion from the data analyzed in the line graph. This is driven by the need to concentrate on clear-cut instances of bias that present less ambiguity. Ambiguous categories can pose significant challenges for analysis, as the motivations behind hate crimes in these groups may be complex and multifaceted, making it difficult to draw distinct conclusions or identify clear trends. By filtering out these complex categories, we can focus on more straightforward cases where the primary bias is against a single group. 

**Visualization #2 (Number of Racially Biased Hate Crimes Over 2021, Percentages of Hate Crimes based on Racial Biases in 2021)**
- Filter on Year: Data was sorted to only include 2021 for analysis because our focus here was to look into the details of hate crimes from the spike in racially motivated hate crimes in 2021, as seen in Visualization #1. Such a temporal focus is essential for understanding the dynamics of hate crimes in the context of an extraordinary event and for assessing whether the patterns observed were a direct consequence of the pandemic-related factors or part of a longer-term trend.
- Filter on Most Serious Bias: Data was sorted to include only Anti-Asian, Anti-Black or African American, Anti-Hispanic or Latino, and Anti-White biases. By narrowing the focus to these specific biases, the graph gives a clearer view of the crimes that were most prevalent and most serious in the social climate of that year. Anti-Arab is excluded from the filtering only because there are no recorded Anti-Arab biased hate crimes in San Francisco in 2021.

**Visualization #3 (Count of Offense Types at Various Locations)**
- Filter on Most Serious Location (The location associated with the most serious crime committed for the hate crime incident): Data was sorted to exclude locations that have record counts of less than 3. Statistically, these outliers might not provide enough evidence to indicate a trend or pattern as compared to the many other categories of location data, thereby skewing the analysis and potentially drawing attention away from areas with more significant data. Visually, the exclusion simplifies the chart, making it easier to digest and interpret by emphasizing locations where offenses occur more frequently. We also excluded “Other/Unknown” locations because this ambiguous category wouldn’t be possible to explain any data about.

**Visualization #4 (Types of Hate Crime Biases and Offense Types on Highways/Roads)**
- Filter on Most Serious Location: Data was sorted to only include records from the “Highway/Road/Alley/Street” category, because the focus analysis here is based on the overwhelming number of incidents at this location, as seen in Visualization #3. 



## Tableau Packaged Workbook





