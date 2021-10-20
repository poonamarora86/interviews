projects in Barclays

1. QA framework: worked on generic quality and process framework. I was the main driver to build the execution side of the framework, detailing best practices in the data analysis projects  to ensure quality of the deliverables. 
There were three parts to it, 
			1. To have peer review on the finished product an analyst has produced. I performed a couple of peer reviews by myself too.
			2. To ensure the quality of data, identify and detect discrepancies in data at source. I collaborated with Execution team to create framework to ensure quality in input data which will eventually mitigate quality issues and discrepancies in final product.
			3. Encourage the developers/analysts to write the tests from day 1, this was done with final goal to make the role redundant in the future.



2. Smart start, money mentors, switcher campaign,  Lookalike 

There are two main areas where retail segment concentrated, acquiring more customers and managing  existing customers by engaging with them efficiently
Below two propositions comes under manage objective where we try to engage with existing customers better

=> Smart start was a proposition targeting kids in the age range of 5-16 with two objectives in mind, first giving kids some financial independence and two inculcating good saving habits in them. My objective was to identify customers who will be interested in the proposition
=> Second proposition namely money mentors was a proactive step towards giving community customers a platform to share their financial issues and get appropriate advice. 
** I helped the team to expand the customer base by identifying similar customers who will be interested in the proposition  
** analyze the behavior of customers who visited money mentors to understand the impact of MM. 
** I analyzed customer behavior on different KPIs like savings, number of products, engagement score, attrition rate, revenue generated for barclays etc. ** Also created a control group of similar customers on three criteria s (hierarchical)
				1. customer living in 15 km of radius where MM was conducted
				2. active in branch at the branch at the same time
				3. age group

The above two propositions became an inspiration for Lookalike model, in both the use cases, the main objective was to expand customer base based on an existing set of audience. This led to creating a generalized and scalable model which can identify similar customers who will be interested in a specific proposition. LAG was also applied to challenger banks where customers were opting for banks like monzo, revolut, starlings over barclays for different services. We create d a lookalike audience who were exhibiting the same behavior as those who were using services from challenger banks and helped us to intervene before the customers left the bank.

3. Scenario planner and customer strategy - Develop a long term strategy for targeting customer groups, rather than sticking to a 1 years plan, stakeholders were interested in a strategy that will be applicable at for least 5 years.
 Product/Model: 1. Rule based segmentation of existing customers based on age groups, Income and engagement level.
				2. Simulation of above segments in next five years using LTV model.

 I contributed in different ways to the team: i) Enriched the segmentation piece by integrating it with various datasets by collaborating with different teams.
										     ii) Developed back end of the tableau dashboard used by stakeholders for targeting and day to day decision making activities (tactical decision making)
										     iii) Enriched simulations by developing an interactive and dynamic dashboard with ability to feed in scenario from users.


4. Mortgage:
	a. Objective: To understand the post maturity behavior in mortgage customers and to increase the proportion of follow-on population which was declining in past decade. The objective can be understood in two stages:
			i) Who goes on follow on or not? 
			ii) Can we find the drivers which impact this decision making process and if we make changes to the appropriate driver/s, will that influence a customer decision? 
	b. Eligible population: All customers who finished their fixed product in a certain time interval. We excluded all those who never finished a fixed period and left us or are still running on fixed product.
	c. Features: We took around 16-17 features including (but not limited to) balance, LTV, original and current rate, follow on rate, payment shock, tenure etc.
	d. Modeling approach: since the main task is to predict whether a customer will go on follow on or not, it became a good candidate for classification. I tried multiple classification algorithms to test the results. One major complexity was involving the imbalanced class distribution as customer choosing for follow on are relatively very less so I had to modify the data to handle the bias. 
	e. Model development: I tried around 5-6 algorithms to test the results on different time periods and found xgboost as the most efficient(in terms of time taken and memory consumption) and most consistent with change in time period and new customers.
	f. Output: Output had two components, an excel which was generated as an output of the model consisting a binary flag identifying whether a customer will stay on follow on or not along with the probability and second it also shows probabilities associated with different variation of follow on rate. Along with this file, a dashboard is also generated which will give some insights on the drivers impacting a customer decision like payment shock and a dynamic component where one can change the follow on rate to see the impact on the proportion of customers staying on follow on rate.
	g. Success criteria: Model success was estimated on precision rather than accuracy as it was a case of imbalanced classes.
	h. Validation: The model was validated in three stages, in time validation, second out of time validation and finally matching the results with existing manual solution.
	i. Current status: last I had produced the predictions for 2021 maturities i.e customer maturing in 2021 to see how much proportion of customer can be retained by optimizing the follow on rate. 
    j. Impact: Increase in even 1% of customers staying on follow on will amount couple of millions of business to barclays.



5. Cards -> I was on-boarded on this project to improve the existing off us spend model which will further be used for targeting campaigns.
Revised thee existing model by upscaling the methodology as well as tech stack. Under review currently.

6. Asset delivery -> The team focuses on creating data assets which can be build and utilized by multiple users in different use cases. The asset is being developed and ingested by an in-house platform named UTEP(unified transactional enriched platform) which enables a user to configure their own datasets.


stakeholder management
1. Short feedback loop used in mortgages project, talking about updates in an interval of one or two weeks where we discussed the progress made along with the future steps. Inquired about stakeholder inputs and accommodate new requirements if possible. 
2. Another thing to keep informing the stakeholder about the scope of the project so they don't create any unrealistic expectation, this is usually communicated via talking about limitations of the project.
3. Detailed documentation handed over to the stakeholder to make the usage easier
4. Knowledge transfer to someone in the team for future refreshes
5. Established processes to get sign-offs at different stages of the project

stakeholder management in Recommendation
1. Identified the issue and communicated the issue with a proposed solution to the project manager
2. She assigned sometime to work on POC
3. Chose one region where I tested the solution 
4. tested it against the existing solution on historical data
5. Showed the results to the manager and to the stakeholders with the KPIs where stakeholders were interested in like Sales qualified leads
6. two points of selling, POC results and easier expansion to other regions. This eventually reduced the time of the analyst in identifying the most suitable customers


example of when you denied that something is not possible - 

a. In mortgages, I denied that the model cannot predict in any other transition beside fixed to follow on.
b. Limitation of UTEP as currently it cannot accommodate any machine learning module. 

Mentored another individual/group
1. ADS
2. organized 20+ sessions on machine learning and testing of hypothesis to on board the team 
3. Helping different individuals to set up and use git, EDP, pyspark



Leadership
1. Led two projects end to end(mortgages and cards) including requirement gathering, estimating work, stakeholder management, setting timelines and presenting deliverables to stakeholders and eventually wider teams
2. Implemented agile practices to develop mortgage and cards model
3. Persuaded cards to change the approach and tech stack to improve overall performance of the model
4. Influenced, envisioned and pro actively developed developed first version of scenario planner
5. Pro-actively presented and communicated LAGto various teams and people including monthly event





