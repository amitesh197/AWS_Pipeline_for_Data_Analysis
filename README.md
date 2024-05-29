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
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/ac957e9e-4e07-443f-80b9-13b67b6696cd)

### - Max Discount Amount

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/5f8bcc9b-90d1-4b02-81e2-a914030f784f)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/abc09ca2-eb4f-480b-97c9-b9a5a347c977)

### - Total Revenue by Client

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/1b0eb9ea-0121-47bd-afc0-51d698dbad36)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/48717f09-4b6e-4df0-bdbb-a1114005138f)

### - Total Clients by Revenue

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/839a7292-7a54-4cd3-a422-b024f2f94b84)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/468b07fc-d537-4db6-be34-6b3c9ab9c223)

### - Each Product’s Total Revenue

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/3729ceed-c25f-46d0-8351-905a9bd80099)
![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/4dc189ca-2919-4fff-8c92-edb1873e8614)

### QuickSight Visualizations:

## - Payment Methods Count

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/e7b3db99-1c31-46dc-98be-c0537524566c)

## - Sales Amount by Client City

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/d41b01d1-6577-4dc6-a6ec-4e3f4cbca045)

## - Discount Amount by Product Category

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/943d8a90-4fbe-49af-bc21-4e3946045ecb)

## - Sales Amount by Product

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/8d2e72f8-71a2-4447-86f3-c5ae0f77513e)

## - Product Category and Sales Amount by Employee

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/0a80a084-e567-45da-9272-13d65c2b79a4)

## - Product Cost by Sale Date

![image](https://github.com/amitesh197/AWS_Pipeline_for_Data_Analysis/assets/123076729/8b58bb7b-38b3-409f-a4da-e37f201d0ac2)


## 8. Conclusion
Leveraging AWS services, this project demonstrated a streamlined data pipeline from ingestion to visualization, enhancing data accessibility and scalability. It empowers stakeholders with actionable insights for strategic decision-making, driving business growth, and optimizing operational efficiency.

## Dataset
- [Kaggle Dataset: Sales data for a chain of Brazilian stores]([https://www.kaggle.com/datasets](https://www.kaggle.com/datasets/marcio486/sales-data-for-a-chain-of-brazilian-stores?select=Sales+Report.csv))
