# BulletProof-DynamoDB-GO
A bulletproof project structure with interfaces in Golang with DynamoDB.

I've used this exact structure for a client's project in early 2021, they have about 6,000 users with 300 concurrent users at any point of time.
This will easily scale to 10k users with zero issues. It will also scale in terms of the team members you can work on this structure with as it has great levels of abstraction
due to the heavy use of interfaces - enabling many people to work together without getting into the nitty gritties.

It's still monolith in nature that means after a while you may not be able to keep adding new functionality without it getting overwhelming. But feel free to use it at
POC stage, at MVP stage and even at production stage till about 10K users. after that I cannot guarantee :)
