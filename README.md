# People Analytics, Human Resources Turnover

# Mindset

1. Regardless of how 'data-centric' or 'data-driven' any given organization may claim to be, data is only as insightful as the willingness to look at it as objectively as possible, i.e., if management asserts anything along the lines of, "this is way we have always done things around here" and/or "while so-and-so may be rough around the edges, they are a top-performer and cannot be replaced", etc., it should give pause the forces of institutional-inertia are likely entrenched. And, depending on how deeply-entrenched, they might just make the resulting 'data' or findings moot.

# 'Data-centricism' 

2. Despite the current 'we are a data-centric' spin any organization may claim, data is still data. In order to maximize data's usefulness, meaning must be derived to positively impact real-world issues, i.e., involving people in actual problem-solving to utilize and apply (said) data's usefulness. The companies hiring based on what employees seek (amongst others 'perks') from permanent work-from-home options to child care support to flex-time to up-skilling to better work-life balance, etc. based on the data verifying some of these quality of life issues either currently are and/or will be truly 'data-driven'.

# Preliminary Work 

1. In a business-setting, an initial consultation with organizational stakeholders would occur to determine the focus and scope of the project.
2. Set timeframe(s) for deliverables. 
3. Provide (regular) status updates 
4. Share initial findings with the Executive Team, e.g., Cost-benefit Analysis including estimates on maintaining status quo versus Change Management initiatives.
5. Upon approval, re-purpose initial findings to be shared with Technical and/or Non-technical staff.  

# Objective(s)
1. Understand what are the factors contributing to employee turnover. 
2. Create a predictive model to determine if a certain employee (type) will leave or stay.

# Analysis
Examined overall employee satisfaction, tenure, and evaluation to determine if they are/were the three main influences determining staff departures.

Conclusion(s):

Employee Satisfaction, Years At Company, Evaluation are/were the biggest factors regarding staff turnover.

1. Low to medium salaried employees had higher attrition rates. Conversely, higher-salaried employees had lower attrition rates. 
2. Highest employee turnover (ranked order) Sales, Technical, Support. Conversely, Management had the lowest employee turnover.
3. High employee turnover 2, 6, 7 projects; most employees with 3, 4, 5 projects remained; all employees with 7 projects left the company.
4. Low to high performance employees tended to leave the most; employee evaluations between 0.6-0.8 tended to remain at the company. 
5. Employees with less hours of work (150 hours or less) or (250 hours or more) had higher attrition rates.
6. Low satisfaction level employees (0.2 or less) or (0.3 to 0.5) and high-satisfaction level employees (0.7 or more) all left the company at higher rates. 
7. More than 1/2 of employees with 4 and 5 years tenure left the company.
8. An average evaluation of roughly 70% meant an employee was likely to stay (even with difference project counts); the data skews towards a high turnover rate after 3 projects or two projects and a lower employee evaluation; employees with more than 3 projects and higher employee evaluations also had higher attrition rates. 
9. Using a Random Forest was the most accurate model for data modeling purposes.

Suggestions: 

Utilize the Kirkpatrick Evaluation Model as part of conducting a Root-cause Analysis - 

1. Reaction - Conduct a company-wide survey of all employees
2. Learning - Based on the survey's results implement on-the-job training aimed at reducing attrition rates
3. Behavior - Monitor if desired improvements are being incorporated or if there is still cultural resistance (to reducing employee turnover)
4. Results - Reduced employee turnover; increased employee evaluation scores 

The above should center on, what are the knowledge, motivation, and organizational solutions to these barriers?

Areas to address include: 

1. Overall attrition-rates
2. Sales, Technical and Support turnover rates, i.e., KPI's; Salary; Management; Career Mobility; finding the possible causes / solutions?
3. Project-related turnover rates; lack of support; level of difficulties; timelines; again, finding the possible causes / solutions?
4. Employee satisfaction; what (if anything) is being done about this? Re-assess management (including Human Resources' policies to find the possible areas where this can be addressed and improved).
5. Employee retention, i.e., in the 4 to 5 year-segment means knowledge, motivation, and organizational is being lost (aside from the people who left with such).
6. Examining why project count; employee evaluation and attrition are correlated and determining (what, if/any) causation.

# Libraries: 

Matplotlib (Data Visualizations)

Numpy (Mathematics)

Pandas (Data Analysis)

Seaborn (Data Visualization)

Scikit-learn (Predictive Analysis)

# References: 

Clark, R. E., & Estes, F. (2008). Turning research into results: A guide to selecting the right performance solutions. Atlanta, GA: CEP Press.

Hofstede, G. H. (2001). Culture's consequences: Comparing values, behaviors, institutions, and organizations across nations (2nd ed.). Thousand Oaks, CA: Sage Publications.

Kirkpatrick, J. D., & Kirkpatrick, W. K. (2016). Kirkpatrick's four levels of training evaluation. Alexandria, VA: ATD Press.

# Appendix: 

People Analytics - 

1. Workforce Planning
2. Talent Sourcing 
3. Hiring Practices 
4. Onboarding / Engagement 
5. Performance Measurement
6. Attrition / Retention 
7. Employee Wellness 

Currently, it seems points 1, 3, 4, 5, 6 and 7 all need detailed, Root-cause Analysis with point 2 being set aside from now (although it could also be an issue influencing attrition).

Proposed Preliminary Discussion with Management would be focused on - 

Institutional-inertia, e.g., 'this is the way we have always done it, etc.' 

Post-findings Discussion would be focused on - 

Reason why these findings (unfortunately) are unsurprising. 

Examples include; 

1. Compensation - examining pay-disparities (what are they?) 
2. Mentorship - are new employees assigned tenured staff to help them to become long-term / successful employees? If, so what is the cost-benefit analysis of this 'initiative'? If not, again, what is the cost-benefit analysis of not implementing this initiative?
3. Promotions - what tangible career advancement opportunities does the company offer? How are these structured? What are the mechanisms for enacting them and ensuring they are implemented as objectively as possible?
4. Management - has a toxic work environment been ignored, e.g., in the Sales, Technical and Support Departments? If so, why has this happened and what are the root-causes, i.e., nepotism, etc.? 
5. Incentives - (classic) carrot versus stick management, i.e., Sales (unrealistic targets); Technical (issues with product releases and not listening to End-user feedback, etc.) and Support (are bugs and/or other issues being reported but ignored?) 

# SWOT Analysis 

Project Strengths: 

1. Working in isolation without being influenced by any unintentional bias, e.g., caused by meeting or speaking with any given employee

Project Weaknesses: 

1. Conversely, working in isolation, i.e., just looking at the data 'clinically' could also not be without any challenges 

Project Opportunities: 

1. The enclosed findings offer an opportunity for this organization to not just conduct an audit but undertake an organizational change initiative

Project Weaknesses: 

1. Conversely, the enclosed findings could be seen as a threat by stakeholders resistant to undertaking an organizational change initiative

# Data Visualizations

1. <img width="1440" alt="Heatmap_Correlation_Matrix" src="https://user-images.githubusercontent.com/48130054/160407762-ee5dd4ca-31fb-43fd-83b2-07df6e53bbab.png"> (Displaying the values based on the color-shading and darkness). Note: The darkness, i.e., satisfaction and turnover.
2. <img width="1440" alt="Avg_Monthly_Hours_Distribution" src="https://user-images.githubusercontent.com/48130054/160567336-402e1f2d-d106-4aa1-85a3-54dd17e3c33e.png"> (Displaying a bimodal data-distribution). Addressing the polarity of too few versus too many hours and creating a better balance is an area to address and remedy.
3. <img width="1440" alt="Emp_Satisfaction_Distribution" src="https://user-images.githubusercontent.com/48130054/161256029-85ef3159-aab0-4baf-8d3f-93474ea98088.png"> (Left-skewed data-distribution).
4. <img width="1440" alt="Emp_Project_Distribution" src="https://user-images.githubusercontent.com/48130054/161301148-3cc2d5cf-70f8-4559-ab1e-722e96c0ddf8.png"> (Right-skewed data-distribution). Compare these two charts and their interrelationship, i.e., dynamic between projects and employee satisfaction. 
5. <img width="1440" alt="Project_Count" src="https://user-images.githubusercontent.com/48130054/161973927-51c9680c-8f24-453f-acf3-345756f8369d.png">(Project count visualization)
6. <img width="1440" alt="Employee_Tenure" src="https://user-images.githubusercontent.com/48130054/162193359-614f330f-7b7f-46ea-811f-a3f6d1c0445a.png"> (Employee Turnover) Note: The highest-level of employee turnover peaks in Year Three with the first two years ascending to that apex. This raises of number of relevant questions from employee on-boarding programs and follow-on training to if more senior-staff are assigned to (even informall) guide and/or mentor junior-staff members. If so, this warrants closer examination, e.g., how are senior-staff assigned; are 360 degree reviews involved, etc. If not, why? Is it a budgetary issue and/or more senior-staff are resistance; un-trained, etc. to actively support junior-staff? Finally, evaluating the effectiveness of assigning junior-staff projects is also another areas to consider for futher review. 
7. <img width="1440" alt="Work_Accidents" src="https://user-images.githubusercontent.com/48130054/162576232-8908108e-98f2-41c1-9771-9c33b7b0321b.png"> (Work Accidents) Note: Briefly, one out of six employees, i.e., just under 17% are involved in an on-site work accident.
8. <img width="1440" alt="Depart_Turnoover" src="https://user-images.githubusercontent.com/48130054/163177683-589f57b5-49bf-49fd-9719-8374f3c16945.png"> (Departmental Turnover) Note: The three highest areas are Sales; Technical and Support.
9. <img width="1440" alt="Salary_Turnover" src="https://user-images.githubusercontent.com/48130054/163183044-772cc53a-bcc9-4c4b-9434-075c5197dc3f.png"> (Employee Salary to Turnover) Note: This goes without saying and no matter how 'obviousness' this may seem, the importance of emphasizing this reality cannot be overstated, i.e., economic-determination is a fundamental reason 'why' people work!
10. <img width="1440" alt="Salary_Attrition" src="https://user-images.githubusercontent.com/48130054/163183957-e10a5404-0d2b-4d90-9de3-db45d9afbdf6.png"> (Employee Salary to Attrition by Tenure) From the lowest to the highest salary-ranges, Year 3 and Year 2 seems to be problematic for this organization. Related to the above points; is this attributed to project-count and/or employee / stakeholder engagement (or lack thereof?) 
11. <img width="1440" alt="Depart_Turnover" src="https://user-images.githubusercontent.com/48130054/164189079-5602552a-4067-461d-aa01-bb97a353b68f.png"> (Departmental Turnover) Again, look at the three areas of highest employee turnover (Sales; Technical and Support) versus the lowest (Management) and it is clearly evident these three departments are problematic.
12. <img width="1440" alt="Emp_Pro_Turnover" src="https://user-images.githubusercontent.com/48130054/164244752-c7567bb7-5e6a-45ab-a9f2-889d331191cd.png"> Project count to turnover, what is driving this? Workload; lack of support; expectations; limited resources; poor management? This area alone warrants closer examination. (Employee Project Count to Turnover)
13. <img width="1440" alt="Emp_Ev_Turnover" src="https://user-images.githubusercontent.com/48130054/164246357-83c52b67-e50f-44d8-852f-27a0207bed76.png"> Lowest (i.e., decreased opportunities; poor management; working conditions, etc.?) and highest (increased opportunities; better management; working conditions, etc.?) employee evaluations result in the greatest turnover. (Employee Evaluation to Turnover)
14. <img width="1440" alt="A_E_Hrs_Turnover" src="https://user-images.githubusercontent.com/48130054/164471224-b686da19-3f4e-48fa-8c64-e5bc2fff4250.png"> Note: Underutilization, i.e., not enough hours and over-utilization, i.e., too many hours result in the two main polarities within this category. (Average Employee Monthly Hours to Turnover)
15. <img width="1440" alt="Emp_Turnover_Ten" src="https://user-images.githubusercontent.com/48130054/165034410-8d688858-4049-4a24-a12e-e9ebc645feb6.png">(Employee Turnover to Tenure)
16. <img width="1440" alt="Emp_WA_Turnover" src="https://user-images.githubusercontent.com/48130054/165322212-c55def46-ce26-4b1a-9bfb-329ec7df6fa8.png"> Whether no accidents and/or one accident, non-Management turnover is significantly higher than Management turnover and could be attributable to the data and supporting details provided above. (Employee Work Accidents to Turnover)
17. <img width="1440" alt="Em_Pro_Turnover" src="https://user-images.githubusercontent.com/48130054/166446646-32ebc14d-07d0-4cd3-8beb-210749a6a0c5.png"> Employees who received a promotion tended to stay at the company (Employee Promotion to Turnover)
18. <img width="1440" alt="Emp_Project_Eval" src="https://user-images.githubusercontent.com/48130054/167287012-c165c1d3-6e18-467d-b9a1-57580c1be60b.png"> Employees with an evaluation-average of roughly 70% tended to stay at the company; the data skews in employee turnover after 3 projects; employees with two projects and a lower evaluation left the company; employees with more than 3 projects and a higher evaluation left the company. (Employee Project Count to Evaluation)
19. <img width="1440" alt="Project_Avg_Hrs" src="https://user-images.githubusercontent.com/48130054/167287134-cfe13ce8-cf36-43d1-8044-e2d45d8e25c2.png"> The average employees worked about 200 hours/month remained at the company; employee turnover for around 150 hours/month or 250 hours/month worked resulted in a higher attrition rate. (Project Count to Average Monthly Hours)
20. <img width="1440" alt="Emp_Sat_Eval" src="https://user-images.githubusercontent.com/48130054/167287276-d4a8dfff-fa3d-4779-8590-eac73e65efb1.png"> (Worked and Dissatisfied with...) Employee satisfaction was below 0.2; evaluations were greater than 0.75, could indicate an employee who put in the work but was unsatisfied with the job, the work environment and/or the company; (Worked and Dissatisfied because...) Employee satisfaction between about 0.35 to 0.45; evaluations were below 0.58, could indicate an employee who received a poor evaluation and as a result felt bad about it or for being at the company itself; (Worked and Satisfied about...) Employee satisfaction between 0.7 to 1.0; evaluations were greater than 0.8, could indicate an employee who was optimal due to being both satisfied with this job who also received a high performance evaluation (which could be self-reinforcing). (Employee Satisfaction to Evaluation)
21. <img width="1440" alt="Emp_Turnover_Cl" src="https://user-images.githubusercontent.com/48130054/167287385-9ffca4f6-b05e-472b-9b30-28a0d329890b.png"> This chart provides a color-based representation (Employee Turnover Cluster)

# Data Modeling - 

23. <img width="1440" alt="ROC_Graph" src="https://user-images.githubusercontent.com/48130054/167287495-5e0251c6-860d-499e-b891-809a24b55ebc.png">Checking for false-positive rates. (ROC Graph) 
24. <img width="1440" alt="Dec_Tree_Class" src="https://user-images.githubusercontent.com/48130054/167287568-9e4c8668-79dc-4283-ba3e-fede2434820e.png">Employee Satisfaction, Years At Company, Evaluation are the biggest factors regarding staff turnover. (Feature Importance by Decision Tree Classifier) 

# End
