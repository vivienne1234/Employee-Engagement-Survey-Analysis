# Employee-Engagement-Survey-Analysis

<img width="457" height="338" alt="Image" src="https://github.com/user-attachments/assets/853da0a2-e32b-4443-98ce-bcf897bb88dd" />

[Click HERE to view dashboard interaction](https://app.powerbi.com/links/BOAJeawZeZ?ctid=c470f255-2be6-4283-868b-c8acfb65ec7b&pbi_source=linkShare)

## Project Overview

This project examines the Pierce County Government Employee Engagement Survey, which collected 14,725 voluntary responses from employees across multiple departments and roles. The survey was designed to capture perceptions of clarity, recognition, growth, inclusiveness, and overall job satisfaction.

#### Response Scale:

0 = Not Applicable

1 = Strongly Disagree

2 = Disagree

3 = Agree

4 = Strongly Agree

#### Dataset Columns:

- Response ID – Unique identifier assigned to each survey entry.
- Status – Indicates whether the survey was completed or left incomplete.
- Department – The department where the respondent works (e.g., Sheriff’s Department, Emergency Management, HR, Finance).
- Role – Job level of the respondent (Director, Manager, Supervisor, or Staff).
- Question – The survey item being answered (e.g., “I know what is expected of me at work”).
- Response – Numeric rating (0–4) selected by the respondent.
- Response Text – Text equivalent of the numeric response (e.g., “Agree”).

#### Survey Questions:
- Q1- I know what is expected of me at work
- Q2- At work, I have the opportunity to do what I do best every day
- Q3- In the last seven days, I have received recognition or praise for doing good work
- Q4- My supervisor, or someone at work, seems to care about me as a person
- Q5- The mission or purpose of our organization makes me feel my job is important
- Q6- I have a best friend at work
- Q7- This last year, I have had opportunities at work to learn and grow
- Q8- My supervisor holds employees accountable for performance
- Q9- My department is inclusive and demonstrates support of a diverse workforce
- Q10-Overall I am satisfied with my job

Together, these columns and questions provide a structured framework for understanding employee sentiment across roles and departments. This description ensures clarity on what the dataset represents before moving into the analysis of findings and insights.


## Data Cleaning & Preparation

### Steps taken before analysis:

- Corrected spelling inconsistencies

  One survey question appeared twice with a minor spelling variation; corrected and merged them.
  
- Compressed role columns

 Merged binary role columns (Director, Manager, Supervisor, Staff) into a single Role column for easier grouping.

## Analysis & Findings

### Question 1

Which survey questions did respondents agree with or disagree with most?

#### Findings:
- Highest agreement:
  
Q1 :- "I know what is expected of me at work" (largest % of “Agree” and “Strongly Agree” combined).

- Highest disagreement:
  
Q6 :- "I have a best friend at work" (largest % of “Disagree” and “Strongly Disagree” combined).

#### Implication:
Employees are confident about job expectations but social connections at work are weaker.



### Question 2 

Do you see any patterns or trends by department or role?

#### Findings:

- By Department:

 Sheriff’s Department shows lower agreement across most questions compared to other departments.

 Emergency Management generally score higher in agreement rates.
 
- By Role:

Supervisors: Highest agreement levels overall.

Staff: Lowest agreement, highest disagreement, particularly on career growth and recognition.

#### Implication:

Frontline staff may feel less supported or recognized compared to leadership roles.




### Question 3 

Which questions had the highest percentage of “Not Applicable” responses?

#### Findings:

Q6 :- "I have a best friend at work" has the highest NA % by a wide margin.

#### Implication:

The question may not resonate with all roles or departments; cultural or role-based differences in interpreting “best friend” at work could influence responses.




### Question 4 

What’s the completion rate of the survey?

#### Findings:

- Completion Rate: 99.08%
- Non-completion Rate: 0.92%

#### Implication:

The survey had very high engagement, making the results reliable.

##### Additional Insights
- Most satisfied role: Supervisors (highest agree %).
- Least satisfied role: Staff (lowest agree %, highest disagree %).
- Potential perception gap: Leadership views workplace conditions more positively than frontline employees.


## Recommendations for Improving Employee Satisfaction

As an employer, based on these results, suggested actions include:

- Strengthen career growth pathways :
  
Clear promotion criteria, mentorship programs, and training opportunities.

- Enhance staff recognition programs :
  
Public acknowledgment, awards, and feedback mechanisms.

- Address department-specific issues :
  
Especially in the Sheriff’s Department, review leadership communication and resource allocation.

- Foster workplace connections :
  
Team-building events, peer mentoring, and cross-department collaborations.

- Clarify the intent of certain survey questions :
  
For example, refine “best friend at work” to “close colleague or trusted peer.”


### Conclusion
The analysis highlights a generally positive sentiment about job clarity but weaker scores on interpersonal and growth-related factors. Differences between staff and leadership perceptions indicate the need for targeted engagement strategies.


