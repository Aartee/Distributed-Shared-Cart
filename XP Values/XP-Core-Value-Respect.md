Week #8

The art of maximizing the amount of work completed is essential. This was the last week for implementation of the project. Each one had dedicatedly worked on their modules and simultaneously worked effectively toward the whole project. 

We had been integrating the modules and trying to make them work. We had various conflicting functions, API and variables. Deciding common terms, respecting each ones opinion played and important role and then we drew a conclusion. 

We have both python as well as nodejs code for backend. The nodejs code is tightly coupled and we had to deploy the backend code for different modules in different clusters according to the requirements. We integrated python code with the UI. Some issues that we faced also included an issue related to free-tier account on AWS. We were not able to create more number of nodes on AWS as per the architecture needs, and so each team member raised a concern/ticket to AWS support, to get the issue resolved as soon as possible.

Overall, we had a long, hardworking week where each team member co-operated and contributed respectfully to complete the project in good shape.

Week #7

This week we were considering all the options of integrating the frontend and the backend codes. We have a backend code which connects to mongodb cluster on aws running in private subnet and connected to a bastion host. The other backend code is the nodejs code which connects to the UI frontend.
We needed to decide whether to put the nodejs and python server code connecting to mongodb cluster together or seperately. In the end we decided to put them separately, where in each module's python backend will be deployed on respective bastion host on each account.

Contrary to python code, the nodejs code will be aggregate of all the 5 modules and will be deployed as one server on a load-balanced instance cluster. Everyone respected this suggestion, and we are going ahead with this options because of it's feasibility and efficiency.

Week #6

This week the CRUD operations for all modules are ready. Everyone has been working on databases using the local databases. Only one teammate have deployed the MongoDB on an AWS cluster and tested the code on the cluster. This is because they are all working on the UI part and will be working on deploying the db on public cloud in the coming week and we respect this decision. 

Also this week, we started working on the User Interface for all the modules. The UI's have been created for 3 modules and is pending for 2 modules. We are also reviewing the options for frontend server and looking to use Nodejs for it. Everyone have agreed upon this and will be working on it's implementation in the coming week. We also need to work on integrating all the components and start end to end testing.

Week #5

This week we have decided to change the NoSQL databases for shopping cart module and User Sessions module, because the deployment of DynamoDB and Redis on AWS is not feasible. Even though we have migrated the databases twice during the project, everyone in the team respected the decision because deploying the NoSQL database as a cluster on AWS is more important than trying different NoSQL DBS for each module. Thus, it has been decided that all 5 NoSQL DB's will be MongoDB which will be deployed on 5 users accounts as seperate clusters.

Also this week we have re-discussed on the system architecture and everyone came up with their feedback, and finally it was decided that Each NoSQL DB API will be placed on the Bastion host for their respective Database cluster. All these API's will be connected as upstream URL's from the web application server and each API call will be routed to respective NoSQL DB API.


Week #4

This week two of the teammates have migrated their NoSQL databases from Riak to DynamoDB and from DynamoDB to Redis. Other people respected the change. Also, this week, we were to decide on the programming language to use for the backend code. We came up with three options namely: go, python and Java. Most of use were inclined to using Go or python as they are very easy to use. But, none of us have worked on Go before and 3 of us have experience in writing code in python. So we decided to use Python for the server side code. Everyone agreed upon this and the others who don't have experience with either language respected the choice. 

Week #3

This week we were looking to finalize the NoSQL databases for the application, but couldn't finalize it. Everyone is not sure about the databases they are planning to use. We all are considering the trade-off between the available NoSQL databases which is causing a delay in project development.

Even though delay is caused we respect everyone's opinion about the delay. This will be helpful in later stages of the project as there won't be mid-project issues with databases changes.

Week #2

This week the Domain of the project was finalized from the 6 available options. It was boiled down to one and we finally decided to go with: Multi-user Online Book Shopping cart service. Though this was not the choice for most of the team members to begin with, everyone measured it's pros and cons and discussed them. The team members respected each other's perspective about the domain and finally settled with it being the domain.

Also, the front end technology to be used was also finalized and Angular JS was chosen. This was an easy choice since lot of team members do not have experience developing the front end. Those who have previous knowledge with front end gave their opinion and the other team members respected their opinion and decided to go with it.

Everyone respects the choice of responsibilities given to each team member during the weekly meeting and also the authority over our own work.

Week #1

Each team member is new to team. Everyone's should give and feel the respect they deserve as a team member. Each member of my team contributed to suggestions and ideas regarding the project. In turn each one respected others opinions also.

During team discussions, we had a lot of ideas coming up from every member. Each one was given opportunity to speak and their ideas where taken into consideration for analyzing pros and cons. We may be wrong in presenting our ideas but each one should maintain esteem and correct the member.

We had conversations regarding start of the project and all ideas the were noted down. We are analyzing each others perspective and then we will select on the process and architecture to be designed
