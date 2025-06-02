# AWS-Serverless-Feedback-System-Automating-Analysis-and-Visualization
This is 4-2 Engineering Project and Iam the Team Lead of this project (Year 2024-2025)
This Project is regarding the Feedback system using Amazon Web Services Platform(AWS).This project aims to automate the collection, analysis and visualization of user feedback using AWS cloud services . 
Users can submit feedback through a web interface, which is then processed and analyzed using AWS Comprehend to determine sentiment .

API Gateway : serves as the entry point for user feedback submissions, handling HTTP requests and securely routing them to AWS Lambda for processing. 

AWS Lambda: processes feedback data without the need for dedicated servers, automatically scaling based on incoming requests.

AWS Comprehend: is a NLP services that analyzes feedback and classifies it as Positive, Negative, Neutral. Here ML models are used to determine the sentiment.

AWS DynamoDB: serves as the primary NoSQL database for storing feedback and sentiment analysis results offering high scalability and fast retrieval.

AWS App Sync: enables real time data synchronization ensuring the sentiment analysis results are instantly updated in google charts.

Google Charts: used for interactive data visualization, allowing administrators to analyze feedback trends over time.
