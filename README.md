# Serverless-Auction-service
 Auction/Bidding System based on Serverless Framework
 
 The project is a simple auction service which is based on Serverless framework.
 
 Functional details of project:
 
 1. Seller can add a new bid and upload photo of the bid.
 2. Buyer can see the currently active bids along with current highest bid price and place a bid.
 3. Sellers and buyer need to login to the service before they can participate.
 4. The bids will automatically close and seller and buyer will get email notification on their respective email.
 
 Technologies used in the project:
 
 1. The project is based on scalable Serverless architecture, which also followings the microservices architecture. 
 2. AWS Lambda, API Gateway to achieve REST API and CRUD endpoints.
 3. AWS DynamoDB is used to store data in persistance way.
 4. AWS SQS (Simple Query Service) is used as message queue to send notification in reliable and scalable way.
 5. Authentication is acheived by auth0 tokens.
 6. AWS S3 is used to store picture objects of the bids.
 7. AWS SES is used to send notification to seller and bidder when the bidding is closed.