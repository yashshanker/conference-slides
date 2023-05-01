# Airflow Unleashed: Toplyne's Transition to a High-Performant, Cost-Effective Airflow Platform

## Long version

In this talk, we will share how Toplyne successfully migrated from Amazon Managed Workflows for Apache Airflow (MWAA) to a custom self-hosted Apache Airflow solution, reaping the benefits of cost efficiency, performance, version control, and improved scaling capabilities. By utilizing AWS services such as Amazon ECS, RDS, and Elasticache, we architected a secure, scalable, fault-tolerant, minimal-maintenance, and robust platform that supports thousands of concurrent DAG executions and allows our engineers to deploy updates in just 2-4 minutes.

We will delve into the key components of our self-hosted Airflow platform, including the use of the Celery executor and integration with Snowflake, Python, and Amazon ECS operators. We will also highlight how our solution achieves up to 30% cost reduction compared to MWAA, provides the flexibility to upgrade to and experiment with latest Airflow versions, and supports REST APIs on top of Apache Airflow to provide enhanced functionality to our Data Platform and Data Science teams.

Moreover, we will discuss the minimal maintenance requirements of our production platform, emphasizing the ease of managing our data pipelines and workflows. By sharing our migration process and the architecture of our self-hosted Airflow platform, we aim to empower other Engineering teams with a production grade self-hosted option to use Airflow, so that they can also leverage this for their specific use cases.

Join us as we recount Toplyne's journey towards a high-performance, scalable, and low-maintenance Apache Airflow solution that surpasses managed services and empowers our data engineers to efficiently build, manage, and monitor complex data pipelines.

-----------------

## Short (1000 characters) version

In this talk, I share how Toplyne migrated from AWS MWAA to our self-hosted Apache Airflow platform, reaping the benefits of cost efficiency, performance, and improved scaling capabilities. I talk about the architecture of a secure, scalable, fault-tolerant, minimal-maintenance, and robust Airflow platform built on top of AWS ECS, RDS, and Elasticache for Redis, that supports thousands of concurrent DAG runs at scale.

I'll dive into the key components of our self-hosted Airflow platform. I also highlight how our solution achieves up to 30% cost for performance compared to MWAA, provides the flexibility to upgrade to and experiment with the latest Airflow versions, and supports REST APIs on top of Apache Airflow to provide enhanced functionality to our Data Platform and Data Science teams.

Through this talk, we aim to empower other organizations with a production-grade self-hosted option to use Airflow, so that they can also leverage this for their specific use cases.