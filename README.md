# Data Analysis Pipeline using AWS Services
# (IAM, S3, Glue, Athena, and QuickSight)

## 1. Introduction
The Superstore Data Analysis Project addresses the growing complexity of retail data at Superstore, aiming to manage, process, and analyze large datasets efficiently. By leveraging AWS services such as IAM, S3, Glue, Athena, and QuickSight, the project seeks to extract actionable insights, driving strategic decision-making and fostering business growth.

### Objectives:
1. **Data Management**: Efficiently manage data ingestion, transformation, storage, and retrieval.
2. **Insights Generation**: Extract actionable insights on sales trends, customer behavior, and product performance.
3. **Scalability and Efficiency**: Handle increasing data volumes without compromising performance.
4. **Cloud Adoption**: Utilize AWS for scalable, flexible, and cost-effective data management.
5. **Visualization and Reporting**: Provide intuitive visualization tools for stakeholders to explore and analyze data.

## 2. Project Goals
- **Optimized Data Ingestion**: Streamline reliable data acquisition through optimized pipelines.
- **Centralized Data Lake**: Create a unified and scalable storage solution for seamless data integration and analysis.
- **Scalable Solutions**: Implement cloud-based infrastructure to handle growing data volumes efficiently.
- **Big Data Analytics**: Use advanced analytics techniques for data transformation, predictive modeling, and decision-making.
- **Interactive Insights Delivery**: Develop visualization tools and dashboards for effective data exploration and communication.

## 3. AWS Services Used
- **AWS IAM**: Manages user identities and permissions.
- **Amazon S3**: Provides scalable and secure data storage.
- **AWS Glue**: Automates data discovery, cataloging, and ETL processes.
- **Amazon Athena**: Enables ad-hoc SQL queries on data stored in S3.
- **Amazon QuickSight**: Offers business intelligence and data visualization tools.

## 4. Dataset Description
The dataset contains 2.6 million records (3.5GB) detailing sales transactions, including company codes, order numbers, employee details, product specifics, and client demographics. This data facilitates analysis of sales trends, customer behavior, and product performance.

### Dataset - 
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/c1f5bebe-f6ab-48b4-bd90-da304d932807)

### Column Statistics - 
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/14f145d7-1be0-41f3-a796-aa0899775a48)


## 5. System Architecture
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/2e304db7-1c18-490d-81ea-745db483f474)

The architecture uses IAM for user management, S3 for data storage, Glue for data cataloging, Athena for querying, and QuickSight for visualization. Data is securely managed and accessible for analysis through these integrated AWS services.

## 6. Data Pipeline
### 1. **Authentication**: Create an IAM user with appropriate permissions.

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/f8631913-a281-46b6-b544-04c9c2764126)



### 2. **Data Storage**: Establish an S3 Bucket for data storage.

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/c41fe41d-d198-449b-a61b-50e954f3922f)



### 3. **Cataloging**: Use AWS Glue to catalog data and create metadata.

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/fd5e45ee-6c05-442b-bd91-3f681ed7b77a)

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/7f8f93a4-66cd-4547-a321-40ff51dc439d)



### 4. **Querying**: Execute SQL queries on data using Athena.

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/0987190b-17bb-440e-8286-aeb642d14b78)



## 7. Result Analysis
### Sample Athena Queries:
### - Distinct Products

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/1f7f08ab-c9ef-4fa8-ae75-c0d0ef09c4c0)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/45002d0c-2038-4540-8e44-70d3e1f40514)

### - Total Records

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/96cf71a8-c2c3-436a-9d29-b18d4b8a2d2a)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/d334ef43-7037-4a35-892a-517c4b9dd9ad)

### - Total Sales Amount

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/6de286ad-ffa7-4ac5-ad1f-e444d9a7c759)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/4215ba07-7560-4771-8e48-099ce71a7114)

### - Average Product Cost

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/74e692ff-b694-48ca-b465-939a51b40442)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/862c2fbe-8427-4878-af87-30a05a3f8f03)

### - Total Sales by Product Category

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/866d8fd2-2676-4b69-8006-26c8ac5c153e)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/aee4a0f4-144d-48e2-8576-ae0570a55834)

### - Employee-specific Records

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/3ea509b8-6ef4-4396-b99f-5493153f284b)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/a3dafb1f-a190-4faa-ae7b-7a11d68fca52)


### - Max Discount Amount

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/401592db-f4c6-4996-9877-957fa4642b39)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/205772b0-ad7b-44bc-84ee-a0db041e6df3)

### - Total Revenue by Client

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/621a04a8-91db-4240-9cd2-d64c4fcb9799)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/a96720da-fd72-4a6c-b872-0fd8dcefdc5c)

### - Total Clients by Revenue

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/a06f760e-52e8-4ced-b981-765930b171f2)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/4b07eb4d-aa7f-4580-9ab1-0f9632762d2f)

### - Each Product’s Total Revenue

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/6cfb3615-7ff1-444d-b1e9-43131a990d02)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/b5d232c4-43b3-4d9e-af4a-e1946ab75bee)

### QuickSight Visualizations:

## - Payment Methods Count

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/abfb4b26-b02e-4208-8952-6997a65e39e1)

## - Sales Amount by Client City

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/59057ce2-d3ec-40e3-938b-dce04dc7b48a)


## - Sales Amount by Product

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/a187acea-565e-4170-a257-058cbb933b2c)

## - Product Category and Sales Amount by Employee

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/396d49bb-eaf8-431f-b018-82a1b30c2657)


## 8. Conclusion
Leveraging AWS services, this project demonstrated a streamlined data pipeline from ingestion to visualization, enhancing data accessibility and scalability. It empowers stakeholders with actionable insights for strategic decision-making, driving business growth, and optimizing operational efficiency.

## Dataset
- [Kaggle Dataset: Sales data for a chain of Brazilian stores](https://www.kaggle.com/datasets/marcio486/sales-data-for-a-chain-of-brazilian-stores?select=Sales+Report.csv)
