---
layout: page
title: "Advice and Coaching"
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
Company X wanted to replace their on-premises data storage solution with a cloud hosted data lake. The team had a defined list of requirements that the new storage solution had to satisfy, including logical separation of data, a central hub to be queried by analysts and rigorous fine-grained access management.

The data team structure within Company X exploited a central team of data engineers which were responsible for ingesting and transforming data, delivering clean ready for analysis datasets which were queried by analysts which sat within their respective departments. To minimise the disruption to their overall team structure, I architected a solution which used discrete Azure storage accounts for the landing, bronze, silver and gold layers. This satisfied the base requirement of a robust cloud hosted data lake in which the data engineering team could apply their existing workflows. To accomodate the need for logical separation, each department had thier own gold layer storage account which segregated the data by department and ensured that access permissions could be robustly set so that each department's data was only accessible by their respective analysts.

The data lake was made secure by restricting access from the public internet and ensuring all resources were behind a private endpoint that only IP addreses from an approved list were allowed access. The least-privilege model was followed, with role-based access control configured to ensure that data engineers and each set of data analysts had only the necessary permissions on each storage layer and data therein. 

## Evaluating success
The new data lake created in Microsoft Azure was presented to Company X stakeholders and received formal acceptance and approval. I also delivered key documentation regarding the configuration, references to best practices and a set of Standard Operating Procedure documents. The data lake solution has been successfully used since delivery and there is ongoing work to extend their exploitation of cloud by implementing analytical workloads within Microsoft Azure.
