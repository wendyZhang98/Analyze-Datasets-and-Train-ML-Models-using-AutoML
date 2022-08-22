# Analyze-Datasets-and-Train-ML-Models-using-AutoML

🎖[AWS AL&ML Tools Summary](https://medium.com/@WenxinZhang98/aws-ml-al-bigdata-8d1f4306d8cf)

### [Week1: Explorethe Use Case and Analyze the Dataset](https://github.com/wendyZhang98/Analyze-Datasets-and-Train-ML-Models-using-AutoML/blob/main/C1_W1.pdf)

🎖Additional Reading Material of Week1:
- [AWS S3](https://aws.amazon.com/pm/serv-s3/?trk=fecf68c9-3874-4ae2-a7ed-72b6d19c8034&sc_channel=ps&sc_campaign=acquisition&sc_medium=ACQ-P|PS-GO|Brand|Desktop|SU|Storage|S3|US|EN|Text&s_kwcid=AL!4422!3!488982706722!e!!g!!amazon%20s3&ef_id=CjwKCAjw6MKXBhA5EiwANWLODMRb8uj_YtDqcbwkSuf10xHCyAP3Hx-iZm0gZZyIK2dSSkVy-M7BCBoCyTwQAvD_BwE:G:s&s_kwcid=AL!4422!3!488982706722!e!!g!!amazon%20s3): Store and protect any amount of data for a range of use cases, such as data lakes, websites, cloud-native applications, backups, archive, machine learning, and analytics.

- [AWS Data Wrangler](https://github.com/awslabs/aws-data-wrangler): Pandas on AWS

- [AWS Glue](https://aws.amazon.com/glue/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc): AWS Glue is a serverless data integration service that makes it easy to discover, prepare, and combine data for analytics, machine learning, and application development. It move data from one location to another, acting as an Extract, Transform, Load(ETL) service. 

- [Amazon Athena](https://aws.amazon.com/athena/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc): Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. (It takes a bunch of CSV or JSON files in a S3 Bucket and load them into temporary SQL tables, so that you can run SQL squeries.)

- Amazon SageMaker: service to build, train, and deloy machine learning models at scale
1) Apache MXNet on AWS: open-source deep learning framework
2) Tensorflow on AWS: open-source machine intelligence library
3) PyTorch on AWS: open-source machine learning framework

🎖Assignment of Week1: Register and visualize dataset

In this assignment you will register and visualize the dataset.
- List and access the Women's Clothing Reviews dataset files hosted in an S3 bucket
- Install and import AWS Data Wrangler
- Create an AWS Glue Catalog database and list all Glue Catalog databases
- Register dataset files with the AWS Glue Catalog
- Write SQL queries to answer specific questions on your dataset and run your queries with Amazon Athena
- Return the query results in a pandas dataframe
- Produce and select different plots and visualizations that address your questions

### [Week2: Statistical Bias & Feature Importance](https://github.com/wendyZhang98/Analyze-Datasets-and-Train-ML-Models-using-AutoML/blob/main/C1_W2.pdf)

🎖Additional Reading Mateiral of Week2:
- [Measure Pretraining Bias - Amazon SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/clarify-measure-data-bias.html)

- [SHAP](https://shap.readthedocs.io/en/latest/)

🎖Assignment of Week2: Detect data bias with Amazon SageMaker Clarify

In this assignment you will detect data bias with Amazon SageMaker Clarify
- Download and save raw unbalanced dataset
- Analyze bias with open source Clarify
- Balance the dataset
- Analyze bias at scale with a Amazon SageMaker processing job and Clarify
- Analyze bias reports before and after balancing the dataset

### [Week3: Automated Machine Learning (AutoML)](https://github.com/wendyZhang98/Analyze-Datasets-and-Train-ML-Models-using-AutoML/blob/main/C1_W3.pdf)

🎖Additional Reading Mateiral of Week3:
- [Autopilot](https://aws.amazon.com/sagemaker/autopilot/)

🎖Assignment of Week3: Train a model with Amazon SageMaker Autopilot

In this assignment, you will train a text classification model using Amazon SageMaker Autopilot. The lab will include the following sections:
- Dataset review
- Configure the Autopilot job
- Launch Autopilot job
- Track Autopilot job progress
- Feature engineering
- Model training and tuning
- Review all output
- Deploy and test best candidate model
