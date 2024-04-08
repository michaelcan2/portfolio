# Data Engineer

#### www.linkedin.com/in/michaelcan2/
#### Long Island City, New York | michaelanthonycan2@gmail.com | (773) 951-8669  


## Skills
Python, Langchain, OpenAI, Microsoft Azure Services, Azure Dev Ops (ADO), Amazon Web Services (AWS), Docker, Snowflake, SQL, NLP, Databricks, Rest APIs, Github, Azure Cognitive Search, NoSQL

# Professional Experience
## Data Engineer @ PricewaterhouseCoopers (PwC) (December 2022 -  March 2024)  New York, NY                                                                                          
### AI Factory Gen AI Functional Specification Documents (FSD) to SQL conversion – Data Engineer 
- Developed a pipeline using Apache Spark Databricks notebooks in Python that takes Functional Specification Documents (FSD) as input and generates a usable SQL query using OpenAI API.
-	Used Azure Cognitive Services (ACS) to store preexisting Functional Specification Documents (FSDs), enabling the retrieval of their corresponding SQL queries. These SQL queries were then utilized as input for the LLM, which generated additional SQL based on the given input.
-	Pipeline reduces development time by ~6 hours, automating the extraction and insertion of information from FSD documents into SQL according to sponsors.

### Test case Generation – Gen AI Developer / Data Engineer
-	Crafted a comprehensive technical architecture illustrating each facet of the pipeline and its operational workflow.
-	Established Retrieval Augmented Generation (RAG) infrastructure integrated with Azure Cognitive Search (ACS) to serve as a robust knowledge base, ensuring the availability of high-quality test cases for reference when generating new test cases for upcoming FSDs.
-	Employed chunking and embedding methodologies to segment multiple test cases in Excel, facilitating their integration through a standardized ADA-embedding model prior to populating them into the ACS index.
-	Managed the Test Case Generation Pod during Agile sprints with Azure Dev Ops (ADO) by establishing features, user stories, and assigning tasks.

### Gen AI Procurement Chatbot MVP – Gen AI Developer / Data Engineer
-	Implemented a Procurement MVP chatbot utilizing Langchain library with the GPT-4 LLM Model.
-	Deployed Minimum Viable Product (MVP) as a secure Webapp through Docker.
-	MVP saves ~8 hours of time eliminating procurement team need to invest in incomplete requests.
-	Prompt engineered MVP tool to educate users on all the necessary information before they can send requests, based on client feedback, to guide users in creating requests.


## Data Engineer @ Sagence Consulting  (March 2020 - December 2022) New York, NY

### Large Academic Institution – AWS Snowflake Architecture
-	Built a reusable code accelerator pipeline for the firm for ingestion of the client’s data from the Client Relationship Management (CRM) Salesforce organization into Snowflake database utilizing AWS services such as API Gateway, EventBridge, Lambda, S3 through CloudFormation.
-	Stood up API Gateway to receive data from CRM; launched an EventBridge to create a validator for the data, ensuring it meets the database’s table structure when updates occur; implemented a Lambda function that filters the JSON data received from EventBridge to specific data points the client defined as resourceful and placed them into S3.
-	Instructed the Snowflake database to use Snowpipe for ingesting preprocessed data into the expected table within Snowflake once S3 was populated with new data.

### Leading Legal Insurance Company – Azure Services NLP Machine Learning Unitization and Metadata Extraction pipeline
-	Engineered a reusable code accelerator for an NLP pipeline, transforming OCR data into structured output integrating different off-the-shelf components for each processing step through the Azure cloud services platform.
-	Built multiple Azure Functions (equivalent to AWS Lambda) to transfer client documents through an Azure Service Bus messaging queue pipeline, facilitating multiple transformations from PDFs to text to JSON document models containing metadata extracted from the specific documents.
-	Established the Microsoft Azure Cognitive Search service, fully implementing it with unitized documents and extracted data. This allows desired metadata to be immediately accessible through search/filter queries.
-	Led Agile sprints to achieve agreed-upon objectives, coordinating and executing corrective actions to address gaps with the client.
-	Developed a text classification algorithm using the spacy Python library to automatically detect entities and key topics within unstructured financial text data and performed further NLP text analysis. Created a Python script for converting OCR documents into text.

### Large Financial Holding Company – Enterprise Data Architecture
-	Constructed requests to an outdoor vendor API through Apache Databricks, and scheduled jobs to establish a Data Ingestion pipeline for incoming data in a distributed system.
-	Analyzed, sanitized, and developed Fact and Dimension tables that populate the Insurance Company’s new Data Warehouse.
-	Automated ETL processes as part of the Company’s ingestion system to update Data Warehouse.

# Education
Northwestern University, McCormick School of Engineering                                                  March 2020
Master of Science in Artificial Intelligence                                                            Evanston, IL 

Coding Dojo, Coding Bootcamp	                                                                             July 2017
Fundamentals of Programming in Python                                                                    Chicago, IL

Columbia College Chicago	                                                                                  May 2015
Bachelor of Arts in Television                                                                           Chicago, IL	

# Certifications
Microsoft Certified: Azure AI Fundamentals                                                      Issued February 2024
Demonstrating proficiency in machine learning and AI principles.                    Credential ID:  84BE9C305FAB7BBD

Microsoft Certified: Azure Data Fundamentals                                                     Issued January 2024
Demonstrating expertise in data principles and Azure data solutions                  Credential ID: 54DA70C0BFB87218               
