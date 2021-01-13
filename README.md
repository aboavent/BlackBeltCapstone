# BlackBeltCapstone
This repository host the code used to develop prediction models in production for classification models in regards to a black belt certification capstone with AWS

The task at hand is describe in the following git page - https://github.com/saidababu/ai-ml-bb/blob/main/week3/day3/capstone/Banking%20Fraud.md


The Juputyer Notebooks in the DataIngestion directory are used and installed on an EC2 Server to obtain data through the Kaggle API.

The Explantory analysis and preprocessing scripts is run under a sagemaker notebook to ingest the data from the S3 Bucket that aws firehose sends the data, transforms it and sends it to the sagemaker buckets - creating training, testing and validation datasets

The Model and Monitoring directory hosts the scripts to develop, train, create models and monitor models
