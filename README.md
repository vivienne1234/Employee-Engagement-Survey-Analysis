# Employee-Engagement-Survey-Analysis

## Project Overview
The dataset analyzed represents voluntary responses from Pierce County government employees to an employee engagement survey.
The goal of this analysis is to identify key themes in employee sentiment, patterns by department and role, and actionable steps to improve workplace satisfaction.

## Dataset Summary
- Records: 14,725
  
- Fields: 10 (Response ID, Status, Department, Role, Question, Response, Response Text, etc.)
  
- Response Scale:

  0 = Not Applicable

	1 = Strongly Disagree

  2 = Disagree

  3 = Agree

	4 = Strongly Agree

## Data Cleaning & Preparation

#### Steps taken before analysis:

- Corrected spelling inconsistencies

  One survey question appeared twice with a minor spelling variation; corrected and merged them.
  
- Compressed role columns

 Merged binary role columns (Director, Manager, Supervisor, Staff) into a single Role column for easier grouping.

## Analysis & Findings

#### Question 1

Which survey questions did respondents agree with or disagree with most?

##### Findings:
- Highest agreement:
  
Question 1 :- "I know what is expected of me at work" (largest % of “Agree” and “Strongly Agree” combined).

- Highest disagreement:
  
Question 6 :- "I have a best friend at work" (largest % of “Disagree” and “Strongly Disagree” combined).

##### Implication:
Employees are confident about job expectations but social connections at work are weaker.



#### Question 2 

Do you see any patterns or trends by department or role?

##### Findings:

- By Department:

 Sheriff’s Department shows lower agreement across most questions compared to other departments.

 Emergency Management generally score higher in agreement rates.
 
- By Role:

Supervisors: Highest agreement levels overall.

Staff: Lowest agreement, highest disagreement, particularly on career growth and recognition.

##### Implication:

Frontline staff may feel less supported or recognized compared to leadership roles.

Question 3 
Which questions had the highest percentage of “Not Applicable” responses?
Findings:
•	Q6 :- "I have a best friend at work" has the highest NA % by a wide margin.
Implication:
The question may not resonate with all roles or departments; cultural or role-based differences in interpreting “best friend” at work could influence responses.

Question 4 
What’s the completion rate of the survey?
Findings:
•	Completion Rate: 99.08%
•	Non-completion Rate: 0.92%
Implication:
The survey had very high engagement, making the results reliable.

Additional Insights
•	Most satisfied role: Supervisors (highest agree %).
•	Least satisfied role: Staff (lowest agree %, highest disagree %).
•	Potential perception gap: Leadership views workplace conditions more positively than frontline employees.


Recommendations for Improving Employee Satisfaction
As an employer, based on these results, suggested actions include:
1.	Strengthen career growth pathways : 
Clear promotion criteria, mentorship programs, and training opportunities.
2.	Enhance staff recognition programs : 
Public acknowledgment, awards, and feedback mechanisms.
3.	Address department-specific issues :
Especially in the Sheriff’s Department, review leadership communication and resource allocation.
4.	Foster workplace connections :
Team-building events, peer mentoring, and cross-department collaborations.
5.	Clarify the intent of certain survey questions :
For example, refine “best friend at work” to “close colleague or trusted peer.”


Conclusion
The analysis highlights a generally positive sentiment about job clarity but weaker scores on interpersonal and growth-related factors. Differences between staff and leadership perceptions indicate the need for targeted engagement strategies.


