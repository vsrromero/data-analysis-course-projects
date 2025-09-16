[English](./README.md) | [Português](./README-pt.md)

# Project 01 – Student Mental Health Analysis

## Project Description
Does going to university in a different country affect your mental health?  
A Japanese international university surveyed its students in 2018 and published a study the following year that was approved by several ethical and regulatory boards.  

The study found that international students have a higher risk of mental health difficulties than the general population, and that **social connectedness** (belonging to a social group) and **acculturative stress** (stress associated with joining a new culture) are predictive of depression.  

In this project, we explore the `students` dataset using PostgreSQL to investigate whether we reach a similar conclusion for international students and to evaluate if the **length of stay** is a contributing factor.  

---

## Project Instructions
- Explore and analyze the `students` data to see how the **length of stay (stay)** impacts the average mental health diagnostic scores of international students.  
- Return a table with **nine rows and five columns**.  
- The five columns must be aliased as:  
  - `stay`  
  - `count_int` (number of international students per stay length)  
  - `average_phq` (average PHQ-9 test score)  
  - `average_scs` (average SCS test score)  
  - `average_as` (average ASISS test score)  
- Round the average scores to **two decimal places**.  
- Sort the results by `stay` in **descending order**.  
- ⚠️ Important: The final solution must use the DataFrame named **`df`** (renaming it will cause issues with validation).  

---

## Data Dictionary

| Field Name     | Description                                         |
| -------------- | --------------------------------------------------- |
| `inter_dom`    | Type of student (international or domestic)         |
| `japanese_cate`| Japanese language proficiency                       |
| `english_cate` | English language proficiency                        |
| `academic`     | Current academic level (undergraduate or graduate)  |
| `age`          | Current age of student                              |
| `stay`         | Current length of stay in years                     |
| `todep`        | Total score of depression (PHQ-9 test)              |
| `tosc`         | Total score of social connectedness (SCS test)      |
| `toas`         | Total score of acculturative stress (ASISS test)    |

---

## Skills Practiced
- Writing SQL queries in PostgreSQL  
- Using aggregate functions (`COUNT`, `AVG`, `ROUND`)  
- Grouping data with `GROUP BY`  
- Applying sorting and aliasing in SQL  
- Interpreting data in the context of mental health research  
The analysis suggests that social and cultural adaptation are crucial for international students’ mental health. Average depression (PHQ) and acculturative stress (AS) do not decrease linearly with length of stay, and social connectedness (SCS) does not automatically improve over time. These findings indicate that length of stay alone is not sufficient to predict mental well-being, and social integration plays a key role in supporting mental health for students abroad.


# Conclusion
The analysis suggests that social and cultural adaptation are crucial for international students’ mental health. Average depression (PHQ) and acculturative stress (AS) do not decrease linearly with length of stay, and social connectedness (SCS) does not automatically improve over time. These findings indicate that length of stay alone is not sufficient to predict mental well-being, and social integration plays a key role in supporting mental health for students abroad.