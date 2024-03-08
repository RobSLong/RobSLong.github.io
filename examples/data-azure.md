---
layout: page
title: "Azure Data and AI"
geometry: margin=3cm
---

More data teams than ever before are experimenting with cloud services to carry out their data, machine learning and artificial intelligence needs. Microsoft Azure is one of the big three cloud providers with offerings covering data storage, transformation and management, and a multitude of AI services including text analytics and image analysis. 
Data analytics distinguishes itself from data analysis because it tells you what to do and what the result will be. Where data analysis gives you information about the current situation, data analytics makes predictions and tells you what the result would be by taking a certain action. In other words: data analysis focuses on the past and current situation, data analytics focuses on the future.

The case below is an example of how I architected a secure data lake solution with logical separations for the different business departments.

---

<img src="/images/goal.png" align="left" width="100px"/> 
How do we migrate our on-premises data solution to the cloud? Can we create a proof-of-concept demonstration to get buy-in from key stakeholders? How do we ensure our cloud solution is secure? These types of questions (and many more) can be answered with implemented solutions by working with me.
<br clear="left"/>

<img src="/images/result.png" align="left" width="100px"/> By exploiting my rich background in data engineering and analytics and recent experience in delivering cloud solutions, I can help architect and deploy proof-of-concept solutions in Microsoft Azure. This data infrastructure can then be used to exploit your data at scale in a secure manner.
<br>
<br clear="left"/>

<img src="/images/duration.png" align="left" width="100px"/>  Project duration varies between 2 weeks – 2 months. The project starts by gaining an understanding of the business and data requirements. After collecting the requirements, I start to document the target configuration and begin the appropriate stream of work; taking on an advisory or hands-on role as appropriate. The final delivery includes documentation outlining the configuration, relevant knowledge articles and a roadmap for future development.

---

## Case - Building a secure data lake
Company X wanted to replace their on-premises data storage solution with a cloud hosted data lake. 

The ability for a business to understand and forecast the job market is vital in being able to write good job postings which entice apropriately qualified candidates. A start-up company was putting together a new data team and had difficulty in attracting applicants for their senior level positions, despite being successful in recruiting junior staff.

To address this problem, a dataset of the company's job postings as well as similar job postings from LinkedIn and Indeed was put together, combining job titles, job descriptions, techonologies, and salaries. In order to decide on the appropriate modelling technique, we need to understand how company X's postings compare to similar job postings.

## Salary Comparison
For the initial exploratory analysis I used _natural language processing_ to perform key-word analysis on the job titles and descriptions but found no distinguishable difference for the posts by Company X. Next, I built a regression machine learning model to estimate the salary as a function of number of years of experience and at first glance this also looked in order. Drilling down into the data, it became clear that there was a geographical bias in the data which required further salary data be collected.

Now, the is a clear distinction between job salaries in the city that Company X is located vs. the average. Accounting for this difference gave actionable insights which were visualised and communicated back to company X.

## Evaluating success
The machine learning (regression) model was packaged up as a code repository and delivered to Company X along with a set of documentation outlining how to use and maintain the code. The monitoring module allowed Company X to observe an increase in applicants for their senior positions from 1 applicant a week to 6. Furthermore, the company have successfully used this model to calculate the starting salary for more recent job vacancies.

