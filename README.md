# School District Analysis
Analyzed the provided data by first cleaning the student names, formatting columns and organizing data into a complete dataframe using Python 3, Pandas and Jupyter notebook. Created new data frames to look at student data by school, student grade data by size of school, student grade data by size of budget and student grade data by type of school. Analysis for UC Berkeley Data Analytics Boot Camp.

## Data
CSV files (in Resources folder) were provided.

## Analysis
Filtered DataFrames using logical operators. Replaced the grades for students in 9th grade at Thomas High School with NaN using the .loc method and recreated school summary data frames to gather test result information. Following is how the data analysis results changed when incorrect test scores were removed.

### District Summary
After the grades were replaced with NaN, the district summar shows little change in the average math and average reading grades, but the passing percentages for reading, math and overall each dropped one percent to the new amounts: 74% passing math, 85% passing reading and 64% overall passing both. 

### School Summary
The school summary shows very little effect on the average math grades and average reading grades for Thomas High School. There were more significant differences in the passing percentage. The percentage passing math changed from 93% to 67% and the percentage passing reading changed from 97% to 70% after the 9th grades were removed from the analysis.

### Thomas High School Performance
Excluding the 9th grade scores significantly changed the standing of Thomas High School. It dropped from 2nd in the district to 8th in the district. 

### Other Effects
The math and reading scores by grade for Thomas High School cannot be compared as the 9th grade has no value for either math or reading in the updated data frame. The scores for the other grades remain unchanged. <br/>

The scores for schools in the $630-$644 spending bracket were affected by the change. The average scores showed no effects but in that bracket, the percentage passing math changed from 73% to 67%, the percentage passing reading changed from 84% to 77% and the overall passing percentage changed from 63% to 56%. <br/>

The scores for schools in the medium size bracket were affected by the change. The average scores showed no effects but in that bracket, the percentage passing math changed from 94% to 88%, the percentage passing reading changed from 97% to 91% and the overall passing percentage changed from 91% to 85%.<br/>

The scores for charter type schools were affected by the change. The average scores showed no effects but in charter schools, the percentage passing math changed from 94% to 90%, the percentage passing reading changed from 97% to 93% and the overall passing percentage changed from 90% to 87%. 

#### Code Sample
![code sample](/images/school_code.png)

## Tech Used
- Python 3.7.3
- Pandas
- Jupyter Notebooks