# People Analytics, Human Resources Turnover

# Goal(s)
1. Understand what are the factors contributing to employee turnover. 
2. Create a model to predict if a certain employee will leave or stay.

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

Utilize the Kirkpatrick Evaluation Model as part of conducting a Root-cause Analysis 

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

Matplotlib

Numpy 

Pandas 

Seaborn

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

Currently, it seems points 1, 3, 4, 5, 6 and 7 all need detailed, Root Cause Analysis with point 2 being set aside from now (although it could also be an issue).

Proposed Preliminary Discussion with Management would be focused on - 

Institutional-inertia, e.g., 'this is the way we have always done it, etc.' is, currently, arguably a reason why these findings (unfortunately) are unsurprising. 

Examples include; 

1. Compensation - examining pay-disparities (what are they?) 
2. Mentorship - are new employees assigned tenured staff to help them to become long-term / successful employees?
3. Promotions - what tangible career advancement opportunities does the company offer?
4. Management - has a toxic work environment been ignored, e.g., in the Sales, Technical and Support Departments?
