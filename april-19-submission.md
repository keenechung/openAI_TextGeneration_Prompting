# SUBMISSION FOR APRIL-19


## What is an API call (answer in your own words)?

* An API call is a request made by one software program to another to access data or perform actions.

* For example: You make an app/software that makes an API call to a weather service like api.weather.com

    - Prompt: "What's the weather in New York?"

    - Respond: {"temperature":"60°F", "condition":"Sunny"}

* Common Actions:

    - GET: retrieve data (e.g., get weather info)

    - POST: send data (e.g., submit a form)

    - PUT: update data

    - DELETE: remove data


## What is an example we discussed to create an API call locally?

* API call can be created locally with fastAPI.

* Running API locally means it is only accessible on your own computer (localhost). There are several good reasons:

    - Safe environment: no risk of exposing data to the public, test and experiment without affecting production systems.

    - Learn and Prototype: great way to learn how APIs work and prototype a project without domain or server. Then later deploy it to cloud providers.


## What is an example we discussed to create an API call on the cloud?

* API can be deployed to cloud providers like AWS (Amazon Web Services), GCP (Google Cloud Platform), or Azure (Microsoft).

* Example of when to deploy API to the cloud:

    - When you want other users to use it.

    - Cloud hosting keep API running live 24/7.

    - Scalability: when API get popular, cloud server can handle more traffic.

    - Integration: plug in with databases, file storage, authentication, etc.


## What is the difference between FastAPI and creating API from AWS Gateway?

* The difference between creating API locally and on the cloud is covered above. 

* Specifically: 

    - fastAPI is a framework used to build APIs with full control over backend logic, it works as an engine that powers your API.
    
    - AWS API Gateway is a cloud service offered by AWS to manage and expose APIs, often routing requests to AWS Lambda or other services without writing backend code. API Gateway is the traffic controller that secures, scales, and routes it in the cloud.


## In your own words after watching the video, what are the main steps to create an API call on AWS Gateway?

* Have an AWS account, and go to account console.

* Create a Lambda function.

* In the Lambda function, add trigger "API Gateway".

* Create API Keys, Stages, Usage Plans, etc. 


## Professionally in the industry, how does developers ship product from one team to another? What's the usage of API here?

* Products are often built by multiple specialized teams (frontend, backend, data, ML, etc.). Each team exposes their service via an API. APIs serve as the "contract" between teams - defining what data is expected, what is returned, and how to call it.

* Usage of API:

    - Isolation: teams build independently but connect via APIs.

    - Speed: parallel developement - now waiting for final implementation, fewer bottlenecks.

    - Clarity: clear input/output, prevent miscommunication.

    - Reuseability: APIs are used by web apps, mobile apps, tools, etc.


