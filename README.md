# 🧠 Analyze Datasets & Train ML Models using AutoML

## 📋 Summary
In this course, I learned how to analyze datasets, detect bias, and train machine learning models using various AWS services.  
Key takeaways include:
- Exploring datasets stored on Amazon S3 using **AWS Glue**, **Athena**, and **Data Wrangler**
- Detecting and mitigating statistical bias using **Amazon SageMaker Clarify**
- Automating machine learning workflows with **SageMaker Autopilot**
- Training text classification models with **SageMaker BlazingText** and understanding NLP algorithms such as **Word2Vec**, **GloVe**, **BERT**, and **GPT**
- Building efficient end-to-end ML pipelines leveraging AWS’s scalable infrastructure

---

## 📘 [Week 1: Explore the Use Case & Analyze the Dataset](https://github.com/wendyZhang98/Analyze-Datasets-and-Train-ML-Models-using-AutoML/blob/main/C1_W1.pdf)

### 📚 Additional Reading
- [**AWS S3**](https://aws.amazon.com/s3): Store and protect data for use cases like data lakes, websites, ML, and analytics.
- [**AWS Data Wrangler**](https://github.com/awslabs/aws-data-wrangler): Pandas on AWS.
- [**AWS Glue**](https://aws.amazon.com/glue): Serverless ETL for discovering, preparing, and combining data.
- [**Amazon Athena**](https://aws.amazon.com/athena): Run SQL queries directly on data stored in Amazon S3 (CSV/JSON).
- **Amazon SageMaker**: Build, train, and deploy ML models at scale.
  - Apache MXNet, TensorFlow, and PyTorch supported.

### 🧩 Assignment: Register & Visualize Dataset
- Access the *Women’s Clothing Reviews* dataset on S3  
- Install and import AWS Data Wrangler  
- Create and list AWS Glue Catalog databases  
- Register dataset files with the Glue Catalog  
- Query data using Amazon Athena and SQL  
- Load results into a Pandas DataFrame  
- Visualize insights and answer analytical questions  

---

## 📗 [Week 2: Statistical Bias & Feature Importance](https://github.com/wendyZhang98/Analyze-Datasets-and-Train-ML-Models-using-AutoML/blob/main/C1_W2.pdf)

### 📚 Additional Reading
- [Measure Pretraining Bias – SageMaker Clarify](https://docs.aws.amazon.com/sagemaker/latest/dg/clarify-measure-data-bias.html)  
- [SHAP (Explainable AI)](https://shap.readthedocs.io/en/latest/)

### 🧩 Assignment: Detect Data Bias with SageMaker Clarify
- Analyze bias in an unbalanced dataset  
- Balance the dataset and compare bias results  
- Run Clarify via SageMaker Processing jobs  
- Review reports before & after rebalancing  

---

## 📘 [Week 3: Automated Machine Learning (AutoML)](https://github.com/wendyZhang98/Analyze-Datasets-and-Train-ML-Models-using-AutoML/blob/main/C1_W3.pdf)

### 📚 Additional Reading
- [Amazon SageMaker Autopilot](https://aws.amazon.com/sagemaker/autopilot/)

### 🧩 Assignment: Train a Model with Autopilot
- Review the dataset and configure the Autopilot job  
- Launch and monitor job progress  
- Perform feature engineering & model tuning  
- Evaluate outputs, deploy, and test the best model  

---

## 📙 [Week 4: Built-in Algorithms](https://github.com/wendyZhang98/Analyze-Datasets-and-Train-ML-Models-using-AutoML/blob/main/C1_W4.pdf)

### 📚 Additional Reading
- [Word2Vec](https://arxiv.org/pdf/1301.3781.pdf) · [GloVe](https://aclanthology.org/D14-1162.pdf) · [FastText](https://arxiv.org/pdf/1607.04606v2.pdf)  
- [Transformer: *Attention Is All You Need*](https://arxiv.org/abs/1706.03762)  
- [BlazingText](https://dl.acm.org/doi/pdf/10.1145/3146347.3146354)  
- [ELMo](https://arxiv.org/pdf/1802.05365v2.pdf) · [GPT](https://cdn.openai.com/research-covers/language-unsupervised/language_unsupervised_learning.pdf) · [BERT](https://arxiv.org/abs/1810.04805)  
- [Built-in Algorithms Docs](https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html)  
- [Amazon SageMaker BlazingText](https://docs.aws.amazon.com/sagemaker/latest/dg/blazingtext.html)

### 🧩 Assignment: Train a Text Classifier with BlazingText
- Prepare dataset  
- Train model using SageMaker BlazingText built-in algorithm  
- Deploy and test model performance  

---

⭐ **Author:** Wenxin Zhang  
📎 *Course Project: AWS Machine Learning Foundations*  
