## Simple Task

This is a simple serverless application using API Gateway for a really silly project I have, I have spent way too much time learning what partition key and sort keys are for dynamoDB, and why I can't just have an static PK, or why I can't use query to act as an scan action, and finally discovering GSI, using my sort key as the partition key in the GSI then querying that sort key. In between, there are a silly ton of mistakes like wrong TableName, wrong permissions in IAM(tricky thing to get the GSI resource in IAM). Ton of other mistakes and understanding which I am very proud I did spend the time and soldiered through, it is defeating at times. But know I have a much stronger understanding of dynamoDB which I never would've had if I did another code along just copy and pasting.

