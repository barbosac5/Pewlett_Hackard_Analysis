# Pewlett_Hackard_Analysis

## Overview
The Purpose of this analysis was to use pgAdmin 4 to determine the number of retiring employees per title, as well as to identify the employees who are eligible to participate in a mentorship program. My objective is to create a report to help prepare for the "silver tsunami" due to the amount of current employees reaching retirement age. 

## Results
### Takeaways for Deliverable 1
For Deliverable 1, I had to create tables that hold all the titles of the employees born between January 1, 1952 and December 31, 1955. I then had to determine the amount of retirement age employees by their recent job title and make sure I do not add those who already left the company. 

-According to the data, there are 90,398 total positions that will be available due to the amount of employees retiring. These positions range from staff members, managers, and senior engineers which can be seen below. One detail I noticed about the data was that there seems to be a vastly disproportionate amount of managers retiring compared to other positions like senior engineers and senior staff. This is most likely because at Pewlett-Hackard, there is one manager that has a lot of staff under them. But it was still odd to see that the managers retiring did not at least break double digits with even the next lowest amount of titles being "Assistant Engineer" with 1,761. 

-This brings me to a similar detail where other positions (such as Assistant Engineer) are vastly overshadowed by the need of Engineers. According to my data, there are 1761 retirees for Assistant Engineer and over 14,221 retirees as Engineers. Like with the managers, I wonder why there is such a large amount of engineers retiring with so few assistant engineers. Perhaps the Assistant Engineers who are still working can help fill the need of engineers when they retire.

#### Retiring Titles 
![Retiring_Titles](./Pewlett-Hackard-Analysis/Pewlett-Hackard-Analysis-Folder/retiring_titles.png)

### Takeaways from Deliverable 2
For Deliverable 2, I was tasked to create a mentorship-eligibility table that holds the current employees born between January 1, 1965 and December 31, 1965. 

-In this table, there are 1,549 employees that are eligible for a mentorship program. Immediately I noticed that due to the table only containing employees born in the year 1965, this table has potential to have much more data of those eligible to participate in the program. An example, would be to not have a restriction based on the birth year. If Pewlett-Hackard allowed not just experienced, but younger employees to participate in this program, there can be even more eligible for the mentorship program.

-Going off the first observation, I also saw that when looking at the mentorship table, there were a lot of senior positions that are eligible to be mentors. I think this can provide an in house training system where before these current employees retire, they can share what they know throughout there time at Pewlett-Hackard. They can teach the younger generation a few tips and tricks to be more productive workers as well as provide insight on how to be a better employee. This can be done in the form of seminars or conferences/assemblies within the company. If done correctly, this can be an endless loop of the older generation teaching the young and can have a continuous stream of experience flow throughout the company.  

#### Mentorship-Eligibility 
![Mentorship-Eligibility](./Pewlett-Hackard-Analysis/Pewlett-Hackard-Analysis-Folder/mentorship_eligibility.png)

## Summary
#### Retirement Titles
![Retirement_Titles](./Pewlett-Hackard-Analysis/Pewlett-Hackard-Analysis-Folder/retirement_titles.png)

This table was used for the beginning of Deliverable 1 and it shows that some employees went through "title changes" throughout their time at Pewlett-Hackard. An example of this is when Christian Koblick became a senior engineer at the end of 1995 when previously, he was classified as an engineer. As more and more employees begin to become senior members, I think it is important to have the younger generation take up the mantle and fill in for those who have moved up the corporate ladder and as well as those who retire. Those who are currently in Assistant positions (such as Assistant Engineer) can rise up to be Engineers and those who are currently enginers can become Senior Engineers if they have the proper credentials and expereince. I believe this is something that needs to be looked into for when we have retirees (as part of the "silver tsunami") who leave and cause gaps within the company. 

#### Unique Titles
![Unique_Titles](./Pewlett-Hackard-Analysis/Pewlett-Hackard-Analysis-Folder/unique_titles.png)

Based on the vast amount of employees retiring, the "silver tsunami" will have a very large impact on Pwelett-Hackard. As stated above there are about 90,398 employees who are eligible for retirement (across all positions) and in addition, the mentorship program only has about 1,549 employees eligible. That is about 58 employees per mentor which does not seem logical in a corporate setting. The only thing that can be done at this time to deal with the impact is to have more employees be eligible to become mentors. One way this can be done is to widen the requeirments to perhaps include more people who were born in 1966 - 1970. While these employees will be younger, they could have just as much or maybe even more experience than some who were born in 1965 alone. Even if this turns out to be false, having more employees to provide help with the enevitabe mass retirement should be welcome. We can have the new hires quickly and efficiently grasp how the company works and how to be efficient as possible. Even getting some outside help in the same field as well as provide more opportunities for mentors to be eligible (as stated in Deliverable 2), can lessen the load on the current mentors to make sure that the next generation is prepared to step in the engineering world of Pewlett-Hackard. 

## Resources
-pgAdmin version 6.8

-postgress version 11.16 
