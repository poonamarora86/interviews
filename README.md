**Motivation and fit**  

	1. What brings you to office  
 		* Freedom of opinion  
   		* Collaborative workplace  
     		* Value generated from what I do 
       		* Team is very diverse in nature which makes this role very relevant to bridge the gaps between sdifferent skillset and expertise and how can we bring value  by bringing them together
       
	2. How Help people - colleagues, customer, commercial

	a. Customer first philosophy - change operating model towards building with customers vs building for customer. Make sure stakeholders are part of your development teams and have direct feedback channel. Agile, iterative, fail-fast etc. 
	b. Futureproofing - always think about wide application of your solution. Design generic solutions that can be reused across various business verticals such as loans, mortgages, savings and cards. 
	c. I would spend time on thinking about creating generic strategies for platforms - find components that can become core for various products. Then build product or domain specific layer on top of it. 
	d. Build culture of knowledge sharing within the team. Run lunch and learn sessions, encourage out of the box ideas, run team hackathons etc.
	e. Working with stakeholders to find where tech and data can improve NatWest's competitive position and thus finding new problems to solve.
	f. Work with leadership to build a culture of bias for action, get things done and work with stakeholders.

**********************************************************************************************************************************

**Experience you have- help you succeed in this role**

I have a decade of experience in data science, data engineering etc. I have also gained understanding of software development, best practices etc. I am scaling my impact by taking more technical leadership role and multiplying my expertise by leading multiple teams, mentoring other data engineers, data scientists and developers. My expertise also helps me to be glue between different organizations, stakeholders and my teams by becoming unblocking agent for them, translating ambiguous business problems into concrete technical projects with plans and processes.

This will give me confidence and authority to do my duties more efficiently in the projects  
New joiner journey - ensuring their 

**********************************************************************************************************************************


**Improved Innovator - Range Checker**

**Situation**: After every pricing proposal, pricing managers need to ensure that the proposed prices do not violate any pricing rules. A simple example being, 60% LTV should be cheaper than products with higher LTV, green should be cheaper than core products etc. Traditionally at the end of proposal, this was done manually by pricing managers, it was time consuming, cumbersome and error prone.

**Task**:  
My task was to design and develop an automated checker for pricing proposals that removes manual efforts from pricing managers and thus reduce any chances of errors.


**Actions**

I conceptualized the idea, validated design with stakeholders and helped prioritise the project within our org. I led the project from conception to delivery, led and mentored a pricing manager and upskilled them in software development, with python as a language. 

I worked with all stakeholders to gather the requirement, define the project scope and led the execution. I broken down the project into multiple milestones, each of those was designed to be working end solution - adding direct value to pricing managers. 

For example, I designed the solution in a way that it separates core logic from presentation, so in the first milestone we could deploy it on existing Excel tool of the pricing managers, making adoption straight forward and gaining trust from them.

I designed solution with future requirements in mind e.g. it can easily accommodate changing rules as well as adding custom new rules. 

I ran project with best practices of software development such as modularising the codebase to make it easy to be deployed to our AWS infrastructure and  easy to debug, led by example to have good test coverage from get go, set up continuous integration to make feedback loops smaller etc. Also ensured that stakeholders are always looped in in every stage of the project.

I am working with the team on Mortgage optimiser on AWS and this is embedded as an integral part of the solution, we are going live in 2 weeks. It allows users to see the violations on the UI for them to make changes to it

I am also designing to make it configurable by the users via UI meaning the users can change the rules easily on the UI and Optimiser will dynamically create pricing for derived products after optimising the core products.

	

**Result**: 

Our solution was immediately adopted by pricing managers, reducing their manual work from several hours to two seconds with ability to add new rules and customize existing easily. Also improved user experience to get all violations in one place, making them easy to incrementally fix one by one - saving another several hours of debugging and testing from their side. 

Collectively we have saved days' worth of work each month for pricing managers for each pricing proposal. As a result of this improvement, we gained trust from pricing managers and that we can leverage in the migration of whole optimiser to AWS and browser based user experience.

**********************************************************************************************************************************

**Connected (Example 1) - Customer data migration to production for Loans**

**Situation**: 
Last year, as part of a strategic initiative, we migrated our loan optimizer to AWS infrastructure. One existential blocker of this project was that customer data that is critical for optimizer wasn't productionized so it was not possible for end users to use the optimizer application. 

**Task**: 
We needed to build a data pipeline to identify, collate and transform the customer data required for the optimizer. Ensure that data is pulled into the systems in near real time into a production system, also avoiding noticeable lag between dev data and production data, improving user experience for our pricing managers.

This was a pretty ambigous problem with dependency on multiple organizations such as D&A who owns the elasticity model, FMA who owns profitability model and PDF org who owns the data pipeline. 


**Action**:
My job was to orchestrate a solution by coordinating with all these 3 orgs and come up with solution that satisfies data governance requirements, analysing trade off of perfect solution against committed timelines. 

I first identified the customer data required for optimizer, worked with different teams to find out current state of different parts of the models and data and their readiness to move it to production. 

Built a shared understanding between all these 3 teams about what it takes to bring all of these models and data to production - identifying biggest blocker as FM&A model which required 6 months to productionize. 

Trade off slipping timeline was big. I then worked to identify a tactical solution that satisfy our data governance requirements. Proposed and got agreement on that solution with PDF team to move only part of the data to production to unblock ourselves. 

I also made sure that everyone agrees on strategic solution and prioritise in their respective teams.


**Result**

Impact was four fold:  
	1. I found a way getting ourselves unblocked with tactical solution that all these orgs agree on as well as satisfy data governance requirements - thus avoiding waiting for 6 months for FM&A team to be ready.  
	2. Technical solution that I proposed and PDF team implemented ensured that data lag is maximum an hour.   
	3. Solution ensured a good end user experience with satisfying all control and data governance requirements.   
	4. All these teams now have a shared understanding of what it takes to productionize end to end pipeline, model and data - thus having a path for strategic solution and having commitments from the relevant teams to move there.  

**********************************************************************************************************************************

**Change Ready - Tech leadership role**

**Situation**: Me along with 2 backend developers and 1 front end developer were tasked to deploy load optimizer to AWS infrastructure. This was the first time we were doing client/server deployment with browser based UI component. Our job was to deploy serve to Kepler and client to PCF. This was a strategic initiative to migrate to cloud for ease of scaling, improving efficiency and improving our readiness for better data governance and controls. 

**Task**: My task was to lead the team to build the system end to end with server deployment on Kepler, client on PCF and snowflake as data backend.

**Action**:
Given this was the first time we were building this kind of architecture, there was no path to follow or learn from. I quickly assumed leadership role, spent time on understanding different components in infrastructure such as Kepler, Snowflake, PCF etc. I digged deep into governance structure, networking details between Kepler and Snowflake. 

Once I had built the understanding, I designed the system with AWS architect and distributed the work amongst other developers. I prepared a project plan with dates, and made sure we are making progress towards it. I became the multiplying agent for the team, helping them with external dependencies, hard blockers and communicating upwards about the progress. I also owned stakeholder engagement end to end, providing timely demos to stakeholders making sure we have feedback loops with them.

**Result**: 
I led a team that built and deployed client/server architecture for the first time in AWS, thus drastically improving scalability story of the optimiser as well as speeding up the process by order of magnitude. e.g. some jobs take 4-5 hours on existing solution vs it takes 30-45 minutes on AWS infra with drastically improving user experience.

**********************************************************************************************************************************

**Critical Thinker/Difference in opinion - Ranking generator**

**Situation**: 

When I joined mortgages for the first time, pricing managers were using a very suboptimal search and rank feature via the excel tool. These features were painfully slow. I identified an improvement and solution to this, that is, a python based solution to cache the search results and only run ranking on it. 

When I proposed the idea, it was challenged being too tactical.  

**Task**: 
Whilst, I agreed that we need a more strategic solution, I strongly believed stakeholders shouldn't put up with bad user experience until perfect strategic solution lands - which could take months. 

This was a living example of "Perfect being enemy of good".

**Action**:

Different of opinion came from my line and project manager. I decided to workshop and brainstorm with him to understand his position better. After a several discussions, I gathered that he is more concerned about we wasting our resources on tactical solution which could have spent on the more strategic solution instead. I challenged that these two things doesn't need to be mutually exclusive.

I then worked to build a solution, in which tactical solution becomes the first milestone of the strategic solution. Created a design that reuses tactical solution components in strategic solution thus, efforts are not wasted on tactical solution. I made sure solution is modularised and can be plugged into different platforms such as excel as well as AWS.

**Result**

In this situation, my critical thinking made sure that user experience improves by providing them tactical solution but at same time addressed the concern of not wasting time by designing it to be reusable in the strategic solution.

**********************************************************************************************************************************

**Trusted Advisor**

**Situation**

In the loan optimizer AWS platformization, one of the key feature ask from the stakeholders were to create folder structure for the scenarios. Existing system already had a tagging feature, which is similar to what they were asking but less user friendly when number of scenarios are large. 

**Task**

Advocate the stakeholder ask in the UI core framework team (PCF) - ensure that this ask is not specialized for loans and applicable for all other optimization solutions.

**Action**

I worked with stakeholders to understand reasoning behind the fold structure. When I understood the ask, I built a plan to introduce it in our core UI framework. I built a case for a feature request by providing detailed reasoning around why tagging feature is not a replacement for the folder structure and how folder structure improves efficiency and user experience of the pricing managers. 

I ensured that stakeholders are looped in all stages of the development to ensure we are building it in the right way. I also demo 'ed the feature to stakeholders in early stages, gathered feedback and looped that back to UI core team. I also made sure that I demo feature in context of other business verticals to ensure feature is built for right level of reuse in mind and it's usable in all the business contexts.

**Result**

At the end, my campaign to champion the stakeholder feature ask with external team and making sure that we are building the most general version of the ask vs special casing it, helped stakeholders build trust in me and transitively in our tech team. Also, having built this feature in the core framework, makes it available to all projects not only just to optimization ones. 
![image](https://github.com/user-attachments/assets/921acc99-e4ab-4792-953e-0f76ca51bc45)



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
										     
										     
## Natwest C11 Interview prep
Improved Innovator: Development of ranking gen
Situation: After having an understanding of current excel based NIm tool, we wanted to upgrade it due to issues like, time, efficiency, scalanility and concurrent usage

a. Not easily scalable or flexible to accommodate new initiatives or range augmentations. 
b. Does not support ongoing use of advanced pricing models/optimisation
c. No integration of elasticity/behavioral/financial models
d. Relies on manual data inputs. i.e. recent trading / defaqto data

Task: Develop a tool which could solve the mentioned issues ensuring no/minimal disruption in their current way of working

Action: 1. Re-defining the problem and modularised the tasks
2. Created a template which is consistent for all modules having details like what the module entails, how data will be populated, what other modules will it contribute to, what module can act as a pre-requisite, peer reviews, functional tests  etc
3. We divided the tasks among oursleves and I started working on the core part of the problem called ranking generator which is essenatially a search engine, it sifts through product data and find out all eligible products w.r.t a search criteria and further ranks them based on different KPIs like true cost, monthly payments with or without fees etc
4. Ensured that development shd be done in such a manner that module can be integrated with other modules as well as can be used standalone. This not only helped with development but also made it easier to do updates or have additional functionalities
5. It also helped with testing

Result: 1. User experience: Since the product has been deployed in their existing user interface(excel based tool), it was very well received
2. Users just need to onboard onto VCSe which was one time task
3. time: Time taken to run the comp tables has reduced drastically as its much faster in python along with it caches teh data which helps with quick rendering
4. Pricing managers are saving 1 hour per scenario which can be very critical in stringent deadlines.
5. We were able to update the codebase for a certain range of products within 2 days which usually took 1-2 weeks for development




Change Ready: backbook implementation
Situation: After deploying the 2 of the core modules of Nim tool, we decided to develop and deploy  back book implementation first before the rest of the modules as we found it could generate more value for the team in near future
Task: Develop and shape the tool by giving back book pricing a priority without making too much chnage on core functionality 
Action: 1. Define the requirements by determining the differences between front book and back book
		2. Create a user friendly  schema which will be flexible enough for the pricing mangers to add/update/delete the different pricing details
		3. Actual development of the functionality by minimizing any changes to the existing tool
		4. Peer reviewed and functional test included
		5. Also used an existing module which flags business violations for every change made by pricing managers
		6. Modifying the code so that it could be delivered such that it can be used by a excel macro
		7. Collaborated with a senior pricing manager to showcase the functionality on timely basis so that the business requirements are take care of
Result: We are estimating that this will reduce pricing managers time by at least 1 hour per scenario

Connected: Presentation to different audience 
Situation: We developed core functionalities for tool along with 2 of the modules went into regular usage, I realised this will be the best time to showcase the functionality to wider audience which included pricing CoE, DnA, FMA and pricing innovation team.
Task: 
Action:
Result:


Critical Thinker: Improving the development process by setting up CI/CD pipelines for other projects
Situation:  After working extensively on development of Nim Tool, I collated my thoughts on drawbacks/limitation and mistakes we did while developing the tool and realsied few things should be thought before rather than as a postmortem, one of them was creating CI/CD pipelines
Task: Objective was to implement learnings from Nim tool development to new projects
Action: 1. Started getting involved in initial phases of other projects and created set ups for other team memebrs
2. Encourange them to use CI/CD pipelines, create pull request so that everythihg we do follows due process
3. Encouraged them to write a basic document for all products and keep documenting alongside rather than at the end
4. Encouraged them to think and write tests to ensure the quality of development
5. Encourage them to use tools like Jira, gitlab, conflunce efficently (for example: not to push any data fileson git or code outputs in notebooks, create regular tickets and update their stages etc)
Result: Team is now following due process and inclines towards test driven development.




connected and trusted advisor

Trusted Advisor: Git/Python training sessions
Situation: 1. Optimisation vertical was new
2. past experience with earnix were not great as they didn't  deliver anything after 3 years for mortgages

remo vs excu
The function automatically pulls key competitors’ retention and new business rates into a report that compares it against our current or proposed rates.
This is used in pricing papers and packs for execs to justify our average front and back book diffs by showing this benchmarked against key competitors.


After staying in the team for a quarter, I realised that there is some interest and curiosity in the team about tech stack and I realised that we can build trust if users (stakeholders) feel comfortable with tech stack being used and reasons for our choices
Task: Knowledge sharing + build trust so that stakeholders are comfortable with what we do 
Action: 1. Documented instructions on set up, 1 group session and multiple 1:1 for set up	
2. Prepared 2 days worth of material on Python coding with some real life examples and conducted full day training with hands on 
Result: 1. Training was very well received in general
2. one of the pricing manager was able to upskill and contribute to Nim tool by developing a whole module end to end (its in usage too) as well as Loans (generate)
3. Another pricing managers from mortgages is using small functionality of python on regular basis and is empowered to make changes at realtime


Side of the desk
connected: 
add more examples 




task:  initiative 

during last year there are few tasks I accomlished 

Collective impact 
trust build up
Made their journeys easier
they feel comfortable with directly coming to me, now we discuss and I bring those requirements to development team and bring them on our development pipelines
and we are adding 

Industry knowledge
Team city, integration, testing 
refactroing

we are moving fast, we are making products, 


Different ideas or opinions - recommendation
Working on blackbox 
bringing people on board

Actions
Spoke to different teams, added their problesm and issues in advance before 
Stakeholder mapping
teams were apprehensive
add that why

applied 20% on the population ML 


Customer centric angle - 
speed to markets changes and 
speed to implementation, 
customer centric, 
life of pricing managers easier


knowledge, experience and why this role is 

technical acumen - 
commercial skills I upskilled, 
pcf


Risk

1. I have been really vigilant about risk from day 1, for my first task of helping with exploring the possibility of granular segmentation of bb customers, I ensured to go through the due process  while accessing the data.
2. I follow bank wide guidelines for using CI/CD platforms for consistency
3. While using gitlab, I ensure that no data has been committed along with notebooks outputs 
4. if there is some sample data being used for testing, I ensure to encrypt it or remove anything PII (personal identifiable information) from it
5. Currently I am migrating an app on PCF, though we are using an existing space (which is goverance ensured), I am engaging with DWS team to understand teh governnace process so we are ready for the future deployments.


Modelling experience










