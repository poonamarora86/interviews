## Innvoation, Proactiveness, Idea generation, Technological mindset

### Cisco recommedendation engine

* Situation

I joined to Cisco's marketing data team to help improve marketing processes. One of the common themes of this team was that we used to
help develop data driven campaigns for marketing people. At this time, we used to manually write rules to find relevant people to target.
This was repetative and inefficient process, data wasn't used to its full potential too. Success rate was pretty low (~5% conversion rate)

* Task

I proposed the team to use Machine Learning to automate and generalize this problem. Task was to demonstrate the value of machine learning to Cisco's marketing team by improving customer conversion and at the same time reducing toil on the data team.

* Action

I worked with Head of Marketing to plan a proof of concept. After looking into data sources (marketing history, browsing data, some third party data sources), I built a model to recommend new products to our existing customers. I also deployed the model along with existing campaign development process.
We used model as well as old processes for a few campaigns to A/B test the effectiveness of the model. I also conducted several training sessions and presentations to onboard the data team and explain how model works to marketing team as well.

* Result

Our POC was hugely successful. Customer conversion rate more than doubled. We reached 35% conversion rate for a certain campaigns which wasn't previously achieved. Model was generic enough to run for relatively different types of campaigns. So we reduced a lot of toil on the team. At the end, Marketing team stopped using old processes and exclusively adopted our model based product. We also improved it further by deploying it on the spark and building explanability dashboard to help marketing team self-serve the understanding and impact.


## Learning, continous improvement, ability to adopt the change, fast paced environment

### Barclays ADS program

* Situation

When I joined the Barclays, I was already quite skilled with data science. But to uplift my skills, I joined Barclays ADS program.

* Task

ADS was a year long program to upskill my data science knowledge by working on a project that impacts Barclays business. Just to be clear, this was extra work outside our normal projects.

* Action

Not only I finished the ADS course but also built a general purpose LookALike model that got used in a few Barclays use cases. Some of which in different teams. We used my ADS project to improve Barclays aquisition propositions such as money mentors and smart start etc.

After that, I also wanted to help others to go through this program to improve data science skillset in the Barclays. I became ADS mentor for one of the follow up batches, co-built interview questions and evaluation criteria, presented on various topics in the program, helped several people in choosing and finishing their ADS project alongwith normal mentorship.

* Result

This not only helped me dig deeper in the data science techniques, practices, improved my mentorship and interpersonal skills but my involvement also helped several other people to upskill their data science knowledge. This in turn helped Barclays business because all these people now will apply these techniques to solve (or improve existing solutions) to their respective business verticals.

## problem solving, challenging decision of others

### Barclays cards off us model

* Situation

At the time when I was working in the central team of data science. Barclays cards team had an off-us spend model that wasn't performing aptly. This was important to work because this model could help Cards team to understand reasons for customers using non Barclays cards and help strategising converting those customers into spending on barclays card.

* Task

I was brought on the team to improve and productionise the model. 

* Action

After reviewing the existing model, I found a few issues with the choice of the model plus had reservations about its scale. When I discussed with the cards project lead, their stance was that we should try to fix the existing model to make it work. In my opinion this was not the right thing to do. The reason for push back was mainly that efforts to build a new model could put the project into risk, which was a reasonable argument. My position was given the data is already prepared and we can re-use the pipeline and we understand the limitation of the existing model, a quick experiment wouldn't be time consuming. So I argued and agreed with project lead to plan for 2 week experiment with new model. 

* Result

It turned out, I could build the new model with better accuracy within that period and disagreement got resolved there. We went ahead with the new model which was significantly better than old as well as it could run on Spark meaning it was very scalable too. Model helped cards team to predict and understand offus spend and improved cards team's ability to increase on-us-spend.   


## 

### Mortgage - Post maturity Retention

* Situation

To understand the post maturity behavior in mortgage customers and to increase the proportion of follow-on population which was declining in past decade. Generally follow on rate is higher than on fixed, it was costing significant losses to the bank, to give you a bit more insight, if we have increased the proportion of follow on population by mere 1%, the business can gain approximately 500k-800K per month (please note that these numbers are fabricated and to protect the privacy of the bank, I cannot reveal the actual numbers)

* Task 

Task can be divided into two:
1. Predict whether a customer will go on follow on or not based on certain attributes
2. To identify which attributes plays a pivotal role in the decision making process

* Actions

For first task , we needed a classifier which could predict whether a customer will go on follow on or not with probabiliy and for second we built a tool which will let the user twaek some of the parameters to see the change in proportion of follow on population.

  1. Data collection: All customers who finished their fixed product in a certain time interval. We excluded all those who never finished a fixed period and left us or are still running on fixed product.

  2. Features: We took around 16-17 features including (but not limited to) balance, LTV, original and current rate, follow on rate, payment shock, tenure etc.

  3. Modeling approach: since the main task is to predict whether a customer will go on follow on or not, it became a good candidate for classification. I tried multiple classification algorithms to test the results. One major complexity was involving the imbalanced class distribution as customer choosing for follow on are relatively very less so I had to modify the data to handle the bias. 

  4. Model development: I tried around 5-6 algorithms to test the results on different time periods and found xgboost as the most efficient(in terms of time taken and memory consumption) and most consistent with change in time period and new customers.

  5. Evaluation: Model was trained on 2 years of data and tested in time as well as out of time dataset. Beside this the results were also validated against manual solution produced by domain experts.

* Result
  Output had two components, 
  1. A table which was generated as an output of the model consisting a binary flag identifying whether a customer will stay on follow on or not along with the probability 
  2. A tool which would allow the user to twaek the follow on rate to see the change in follow on rate (individually as well in group)
  3. A dashboard is also generated which will give some insights on the drivers impacting a customer decision like payment shock 


  ### Eero upsell

 * Situation
UW launched a new product which could provide great network connectivity in the households. Our first audience for this product were our existing broadband customers.
In our first rue based marketing campaign, we reached approximately 1% upsell 


* Task

DS team was invited to help increase the upsell

* Actions

1. We pulled demograhic, property, internet and technology usage and behavioral features for our customer based features for our existing custoemr base
2. We used the success events from first marketing campaign as our source population and  mapped them against rest of the population
3. Used a distance based algorithm which could quantify similarity between two customers and ranked them on their similarity 
4. Provided first set of ranked customers to the marketing team to launch another reachout campaign

* Results

1. We reached 3.4% upsell in our 2nd DS based marketing event
2. This led the team a automated pipeline which will feed into the marketing databse with most eleigible population
3. In future, we will be generalising the pipeline for multiple use cases


## stakeholder management
1. Short feedback loop used in mortgages project, talking about updates in an interval of one or two weeks where we discussed the progress made along with the future steps. Inquired about stakeholder inputs and accommodate new requirements if possible. 
2. Another thing to keep informing the stakeholder about the scope of the project so they don't create any unrealistic expectation, this is usually communicated via talking about limitations of the project.
3. Detailed documentation handed over to the stakeholder to make the usage easier
4. Knowledge transfer to someone in the team for future refreshes
5. Established processes to get sign-offs at different stages of the project

## stakeholder management in Recommendation
1. Identified the issue and communicated the issue with a proposed solution to the project manager
2. She assigned sometime to work on POC
3. Chose one region where I tested the solution 
4. tested it against the existing solution on historical data
5. Showed the results to the manager and to the stakeholders with the KPIs where stakeholders were interested in like Sales qualified leads
6. two points of selling, POC results and easier expansion to other regions. This eventually reduced the time of the analyst in identifying the most suitable customers


## example of when you denied that something is not possible - 

a. In mortgages, I denied that the model cannot predict in any other transition beside fixed to follow on.
b. Limitation of UTEP as currently it cannot accommodate any machine learning module. 

## Mentored another individual/group
1. ADS
2. organized 20+ sessions on machine learning and testing of hypothesis to on board the team 
3. Helping different individuals to set up and use git, EDP, pyspark



## Leadership
1. Led two projects end to end(mortgages and cards) including requirement gathering, estimating work, stakeholder management, setting timelines and presenting deliverables to stakeholders and eventually wider teams
2. Implemented agile practices to develop mortgage and cards model
3. Persuaded cards to change the approach and tech stack to improve overall performance of the model
4. Influenced, envisioned and pro actively developed developed first version of scenario planner
5. Pro-actively presented and communicated LAGto various teams and people including monthly event

## QA framework in barclys to support externlal client facing team

QA framework: worked on generic quality and process framework. I was the main driver to build the execution side of the framework, detailing best practices in the data analysis projects  to ensure quality of the deliverables. 
There were three parts to it, 
			1. To have peer review on the finished product an analyst has produced. I performed a couple of peer reviews by myself too.
			2. To ensure the quality of data, identify and detect discrepancies in data at source. I collaborated with Execution team to create framework to ensure quality in input data which will eventually mitigate quality issues and discrepancies in final product.
			3. Encourage the developers/analysts to write the tests from day 1, this was done with final goal to make the role redundant in the future.

## Smart start, money mentors, switcher campaign,  Lookalike 

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

## Scenario planner and customer strategy - Develop a long term strategy for targeting customer groups, rather than sticking to a 1 years plan, stakeholders were interested in a strategy that will be applicable at for least 5 years.
 Product/Model: 1. Rule based segmentation of existing customers based on age groups, Income and engagement level.
				2. Simulation of above segments in next five years using LTV model.

 I contributed in different ways to the team: i) Enriched the segmentation piece by integrating it with various datasets by collaborating with different teams.
										     ii) Developed back end of the tableau dashboard used by stakeholders for targeting and day to day decision making activities (tactical decision making)
										     iii) Enriched simulations by developing an interactive and dynamic dashboard with ability to feed in scenario from users.
