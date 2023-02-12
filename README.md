# Lab 3
[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repo and clone it to your machine to get started!

## Team Members
- Raymond Sabino

## Lab Question Answers

Answer for Question 1: 
    RESTful APIs are scalable because they are stateless, meaning there is less server load since the server doesn't need to retain information on past client requests. This prevents communication bottlenecks that would come if this information needed to be passed for every interaction.

Answer for Question 2:
    The mail server is providing clients text resources by storing, displaying, and sending to other clients their emails
    
Answer for Question 3:
    One common REST method not used in the mail server is PUT. We could incorporate this into our mail server by implementing an edit email function so there is a need to update a REST resource rather than just retrieve, create, or delete them.
    
Answer for Question 4:
    API keys are used for so many RESTful APIs because the hosts of the APIs want to limit requests made, so to track this for individual clients, they use API keys. Its primary purpose is to limit use of their API or certain API methods to certain users. Some use this to monetize use of their API. Information used for this answer came from: https://cloud.google.com/endpoints/docs/openapi/when-why-api-key
