# BIM app
Consists of three modules<br>
* Data management module<br>
* Query engines— Natural Language Processing Module <br>
* User interface<br>

# Data Management Module
The development of the Data Management (DM) module for the Building Information Modeling (BIM) Information Retrieval (IR) involved several steps to prepare high-quality data. These steps included data extraction, transformation, cleaning, classification, and importing into a database.<br>
#### Step1: Conversion of BIM file to IFC format<br>
#### Step2: Conversion of IFC format to JSON document<br>
#### Step2.1: Import JSON file into database<br>
#### Step3: Validate JSON document against IFC JSON schema<br>
#### Step5: Data extraction<br>
#### Step6: Data preprocessing<br>
#### Step6.1: Convert it to dataframe
#### Step6.2: Data concatenation
#### Step7: Data classification<br>
#### Step8: Importing data into database<br>
We are importing the cleaned data into the cloud-based MongoDB database. The data are stored as documents in BSON format, which allows
for flexible and efficient querying <br>
http://18.170.83.79:8081/db/admin/Json_Files<br>
#### Step9: Transforming data into vector embeddings<br>
Step9.1 Use of the BERT model<br>


# References
* https://www.google.com/search?q=bim+chatgpt&oq=bim+chatgpt&aqs=chrome..69i57.2853j0j4&sourceid=chrome&ie=UTF-8#fpstate=ive&vld=cid:a51e47e7,vid:fMEiDrjlaTE
* https://arxiv.org/pdf/2304.09333.pdf
* https://arxiv.org/pdf/2302.10205.pdf
* https://leanpub.com/langchain/read#basic-usage-and-examples
* https://github.com/OpenDataBIM/data-analytics/tree/main
