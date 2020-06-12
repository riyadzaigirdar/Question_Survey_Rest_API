# Question_Survey_Rest_Api


Tasks:

Develop an API with the following requirements using Django Rest Framework: (recent version is preferable)

a. Prepare a questionnaire/survey. The question should have name only and allow free text answer (limited to answer yes and no). Here is the is a sample question - Are you using Django Rest Framework? and sample answer: Yes or No

b. There will be two user roles, Admin and User

c. Admin can create/update/view question

d. User is able to response to question and view his/her own response only

e. Admin can view all responses

f. Use Token authentication


Requierements:

The endpoints should be:
Create questions (/api/v1/question/ POST)
Update questions (/api/v1/question/:id/ PUT)
View list of questions (/api/v1/question/ GET)
Answer to question (/api/v1/qanswer/ POST)
View answer (/api/v1/qanswer/ GET)


Use following Technology Stack:

DRF latest version is must 
Django ORM is must 
Postgres is a plus 
Docker is a plus
