AWS Lambda serverless
=====================

event -> function -> services

Nearly all services of aws trigger a lambda.
- Bring your own code
  - Node, Java, Python, .NET
- Flexible use
- Simple resource model
- Flexible authorization
- Authoring function
- Programming model
- Monitoring and logging

How event sources work
----------------------
- synchronous model
- asynchronous push model
- stream pull model


AWS X-Ray -> Monitoring & Debugging!!!! <- LOOK THIS! = New service
---------------------------------------------------

Uses cases
-----------

Webhooks! <- match with lambdas

Frameworks
---------------
APEX, sparta, ...

Monolithic  -> microservices

SAM (Serverlees Application model)
----------------------------------

Help manage a lambdas microservices.
simplifies deployment
Supported by aws cludformation
Export any function as a sam template

CI/CD with SAM
---------------------
commit(github, aws code commit) -> build (aws codebuild) -> test (aws code build), deploy(aws cloudformation)

AWS CodeStar
--------------
Manage all flow before
Beautiful Dashboard
Ruby supported, appeared

Big data and aws lambdas
------------------------
- MapReduce
- Batch
