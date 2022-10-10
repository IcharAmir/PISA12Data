# (PISA Data 2012)
## by (Charles Baba Odogun)

## Dataset

PISA is a survey that examines students from compulsory education on how well prepared they are for life after school. This investigation focuses on the PISA Survey from 2012, with data belonging to around 500K students from 65 different countries.

The dataset provided by Udacity contained data from a total of 485'490 students, grouped in 636 columns.
The dataset contains not only the results from the exam in each category, but also lots of information on the students' background, including variables like country of residence, number of family members and their level of education, possessions or access to different facilities at home and at school.

The main feature of this dataset is the score obtained by the students in each discipline and the potential for understanding how a number of different background factors can impact these scores and therefore the level of preparation for students around the world.

Analyzing such a complex dataset entirely requires a lot of time. For this project, I used the following variables from the dataset :

- "CNT","Country code 3-character"
- "OECD","OECD country"
- "NC","National Centre 6-digit Code"
- "SCHOOLID","School ID"
- "ST04Q01","Gender"
- "ESCS","Index of economic, social and cultural status"
- "FAMSTRUC","Family Structure"
- "HISCED","Highest educational level of parents"
- "PV1MATH"
- "PV1READ"
- "PV1SCIE"

In addition to these variables, I kept the results for the three main disciplines: maths, reading and science.

## Summary of Findings

The exploratory analysis provided the following findings:
1. Mexico has the highest number of students with 33806, followed by Italy with 31073,Spain with 25313 and Canada 21544 students. 
2. Alot of the students come from the average household according The students economic,social and cultural status 
3. We see that alot of the students come from a 2 family structure, over 350.000+.
4. Alot of the student parents have a ISCED 5A,6 education level.
5. All score variables follow a normal mean distribution,with scores ranging from 200 - 800 points and from all 3 scores we can see that majority of the students have the mean score of 500 points
6. Students from OECD countries are higher than Non_OECD
7. The difference between the female and male students is really not too significant but there are more female students. 
8. Also,in terms of performance,in maths boys did more than girls, in reading girls were better readers and in the science, there isnt much difference in their perfomance. 
9. OECD country performed better in all 3 ,ie mathematics,reading and science than the Non-OECD 
10. China comes top in all the subjects, followed by Hong Kong, Singapore , Vietnam.
11. Using the level of parents education, we will see that students who filled thier parents highest educational level as ISCED 5A 6, scored higher than others. 
12. There is a high correlation between science and math (r=0.9) and science and reading (r=0.88), and math and reading (r=0.86).
13. Using the OECD status, both OECD and Non-OECD countires , have less students from a 3 family structure. and favor a 2 family structure and their different perfomance is not really significant. 



## Key Insights for Presentation

In the presentation, I showed the correlation between the scores obtained by students in each of the 3 disciplines.
Then , tried to identify the relationship between each of the independent variables(gender and countries) with the scores, using the bar, histogram in the exploratory visualization.


```python

```
