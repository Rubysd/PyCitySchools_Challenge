# PyCitySchools_Challenge

# Overview of the school district analysis: Explain the purpose of this analysis
The purpose of the project is to analyze data provided from High Schools before and after possible academic dishonesty, where the data for Thomas High School 9th grade has been kept for the purpose of analysis. We have replaced Thomas High School's math and reading scores with NaN, keeping the rest of the data intact. We will analyze the data before and after making this change.

# Results: Using bulleted lists and DataFrames images as support, answer the following questions
How is the district summary affected?
# DISTRICT SUMMARY BEFORE 
![image](https://user-images.githubusercontent.com/86340630/126075475-d2d78d22-542a-41ae-a077-817ac3cdcdb2.png)
# DISTRICT SUMMARY AFTER
![image](https://user-images.githubusercontent.com/86340630/126075568-018cd349-335a-4636-9911-399af7940a28.png)

District summary analysis

Let's start with the average scores in math and reading fell by just 1%, that is, from 79% to 78% and from 81.9% to 80.9%, respectively. Later it can be seen in the images that we see that the data is not affected in terms of total schools, total students and total budget. Lastly, it can be seen that the math passing rate, the reading passing rate, and the overall passing rate also showed a 1% drop after the change from 75% to 74%, 86% to 85%, and 65%. to 64%, respectively.

How is the school summary affected?
# SCHOOL SUMMARY BEFORE
![image](https://user-images.githubusercontent.com/86340630/126075772-7516ee34-796d-4854-9f35-072c1b695e31.png)
# SCHOOL SUMMARY AFTER
![image](https://user-images.githubusercontent.com/86340630/126075807-49e48296-ce5e-4147-aea6-6f28d316b1c0.png)

School summary analysis

As we can see the before and now images, the percentage of students passed in math and reading at Thomas High School dropped considerably from 93.27% to 66.91% and from 97.31% to 69.66% respectively, then we can see that the data is unaffected in all schools.
Thomas High School is the only affected school that showed a drastic drop in all grade parameters and passing rates. Thomas High School's average math score and average reading score changed markedly from 83.42 to 59.85 and from 83.85 to 60.24 respectively after the data change.

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
# MATH AND READING SCORES BY GRADE
![image](https://user-images.githubusercontent.com/86340630/126079885-5ba01e77-9e1d-4112-9935-71a5dbc4f033.png)
# AVERAGE MATH SCORE BY GRADE BEFORE 
![image](https://user-images.githubusercontent.com/86340630/126079936-11e58373-b9f5-4a54-84a2-089aade3854b.png)
# AVERAGE MATH SCORE BY GRADE AFTER 
![image](https://user-images.githubusercontent.com/86340630/126079963-7a6075eb-0762-4199-bb61-dff518668e36.png)
# AVERAGE READING SCORE BEFORE 
![image](https://user-images.githubusercontent.com/86340630/126080025-7a1e3964-6ba4-4809-acba-a0deca909a48.png)
# AVERAGE READING SCORE AFTER 
![image](https://user-images.githubusercontent.com/86340630/126080041-577e8aa4-2c29-4efb-9143-164c7bfa6262.png)

Analysis math and reading scores

As we can see the data is not affected in all schools except Thomas High School, which showed a drastic drop in all grade parameters and in the passing percentage, you can see that the percentage of students passing in math and reading Thomas High School's average score dropped significantly from 93.27% to 66.91% and 97.31% to 69.66%, respectively, and Thomas High School's average math score and average reading score drastically changed from 83.42 to 59.85 and 83.85 to 60.24 respectively after the data change.

How does replacing the ninth-grade scores affect the following:
Math and reading scores by grade
![image](https://user-images.githubusercontent.com/86340630/126080715-9c1582a9-dae0-4c0f-8890-8d2dbe250831.png)

Math and reading scores by grade
First we start the percentage of approved students in general dropped to almost 25%, we can see based on the data that the average math score and the average reading score fell to 23-25 we can also see that the percentage of students Passing in math and reading dropped to nearly 27%.

Scores by school spending
# SCORES BY SCHOOL SPENDING BEFORE
![image](https://user-images.githubusercontent.com/86340630/126080449-bcd88525-90b8-4ba4-8d0a-cbb2fcddb7be.png)
# SCORES BY SCHOOL SPENDING AFTER 
![image](https://user-images.githubusercontent.com/86340630/126080460-5b246c15-c8fc-4a99-b211-89a07035c4a1.png)

Scores by school spending analysis
Since Thomas High School fell into the category of spending range per student of $ 630- $ 644, the average scores in math and reading dropped from 78.5 to 72.6 and from 81.6 to 75.7 respectively, it can also be seen that the passing percentage in math and reading decreased from 73% to 67% and from 84% to 77%, respectively, as students who passed decreased from 63% to 56%. Data at rest was not affected

Scores by school size
# SCORES BY SCHOOL SIZE BEFORE
![image](https://user-images.githubusercontent.com/86340630/126080810-329548b8-f9a3-4c14-9a35-5cef9071ec3b.png)
# SCORES BY SCHOOL SIZE AFTER
![image](https://user-images.githubusercontent.com/86340630/126080831-7cbc5d8c-d444-4473-9a08-020f76dd54fe.png)

Scores by school size analysis
You can see that Thomas High School fell into the middle category (1000-2000) you can see that the average scores in math and reading dropped from 83.4 to 78.7 and from 83.9 to 79.1 respectively. and the passing rate in math and reading decreased from 94% to 88% and from 97% to 91%, respectively. To conclude, students who passed decreased from 91% to 85%. Data at rest was not affected.

Scores by school type
# SCORES BY SCHOOL TYPE BEFORE
![image](https://user-images.githubusercontent.com/86340630/126081005-6d265f33-1fe9-4e2f-b55b-b2e32d5ecdb7.png)
# SCORES BY SCHOOL TYPE AFTER
![image](https://user-images.githubusercontent.com/86340630/126081014-ace566ce-c04c-4678-95f9-409211eb65b9.png)

Scores by school type analisys
Average scores in math and reading dropped from 83.5 to 80.5 and from 83.9 to 80.9 respectively and the passing rate in math and reading decreased from 94% to 90% and from 97% to 93%, respectively, you can see that students who approved decreased from 90% to 87%. Data at rest was not affected.

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
First, the average in math and reading decreased slightly at the district level, but dramatically at the school and grade level after the change.
Subsequently Thomas High School, which was ranked second, dropped out of the top 5 schools to rank 8 after the change.
As we can see, the percentage of students passing math, reading, and general was also significantly affected at Thomas High School's school and grade level after the change.
All academic benchmarks related to math, reading, and overall score dropped dramatically for whatever school type, size, and spending by student category Thomas High School was in.







