# AWS-Sagemaker
Discussion on AWS Sagemaker
# What problems does Sagemaker solve?

AWS SageMaker was designed with the focus on seamless adoption by the machine learning community and easy deployment of trained models to production.It offers python and Jupyter Notebook — everything we normally use to play with Machine Learning. And no special configuration is required to start training some model remotely in the Cloud.
First you spin up a so called “notebook instance” which will host the Jupyter Notebook application itself, all the notebooks, auxiliary scripts and other files. No need to connect to that instance (actually you cannot, even if wanted to) or set it up in any way. Everything is already prepared for you to jump into some exiting Machine Learning! Create a new notebook and use it to collect and prepare some data, to define a model, and to start the learning process.All from one place, using python, popular ML frameworks and SageMaker’s own libraries.
Speaking of frameworks and libraries, SageMaker supports TensorFlow and Apache MXNet out-of-the-box. It also comes with some built-in algorithm, for instance,PCA, K-Means and XGBoost. You can even use Apache Spark to pre-process the data. If this is not enough, if you want to use your own favorite framework or maybe even another programming language, well, you can. It won’t be as simple, but you can package any machine learning algorithm into a Docker container and plug it into SageMaker’s training-serving pipeline.

# What are competitive offerings to Sagemaker?

  # Amazon Machine Learning

This new AWS service helps you to use all of that data you’ve been collecting to improve the quality of your decisions. You can build and fine-tune predictive models using large amounts of data, and then use Amazon Machine Learning to make predictions (in batch mode or in real-time) at scale. You can benefit from machine learning even if you don’t have an advanced degree in statistics or the desire to setup, run, and maintain your own processing and storage infrastructure.

  # Databricks

Databricks Unified Analytics Platform, from the original creators of Apache Spark, unifies data science and engineering across the Machine Learning lifecycle from data preparation to experimentation and deployment of ML applications.

  # Azure Machine Learning

Azure Machine Learning is a fully-managed cloud service that enables data scientists and developers to efficiently embed predictive analytics into their applications,helping organizations use massive data sets and bring all the benefits of the cloud to machine learning.

  # TensorFlow

TensorFlow is an open source software library for numerical computation using data flow graphs. Nodes in the graph represent mathematical operations, while the graph edges represent the multidimensional data arrays (tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API.

Post a screenshot of a lab where you had difficulty with a concept or learned something.
