# Data framework for ai Solutions in AEC industry

>Transform scattered processes into streamlined, assembly-line-like procedures forming a more factory-like paradigm.

<br><br>
### Why we build this framework<br>
Challenges we address:`Friction` `Lack of Data` `Uneven Information Distribution` `Safety` `Low Productivity`<br><br>
The **property development industry** is characterized by **inherent challenges**, such as **friction** between parties due to **uneven information distribution, safety concerns**, issues related to **quality**, and **low productivity.**<br><br> 
By linking the myriad of stakeholders involved in property development processes via streamlined information sharing, we can mitigate these fragmented procedures. <br><br>
The expected outcome is a transformation of disjointed steps into a seamless, assembly-line-like operation, effectively morphing the process into a more factory-like paradigm.<br><br>





# 1. Connect Your data sources to AI engine
Integrate Your Data Sources with Our AI Engine: **Unlock** the potential of **untouched data reservoirs**. Transform every piece of information into a valuable data source. Accumulate, order, and systematize data to construct an all-encompassing knowledge base.<br><br>
<img width="624" alt="Screenshot 2023-06-15 at 22 28 19" src="https://github.com/phaethonp/we-ai/assets/33053426/058b2632-22b6-4c07-81bd-841ee92fc43a">
<br><br>
# 2. Create a Data Warehouse from Raw, Structured, or Unstructured data 
Consolidate all your data in one location to establish a unified source of information. <br>

<img width="1208" alt="Screenshot 2023-06-15 at 22 52 56" src="https://github.com/phaethonp/we-ai/assets/33053426/f3feb841-b4f9-41b2-8867-bc2bcc09e714"><br>
# 3. Query unstructured data with natural language

<img width="1024" alt="Screenshot 2023-06-15 at 23 43 13" src="https://github.com/phaethonp/we-ai/assets/33053426/12df28b9-036c-43ad-8e31-074bc4669bac">
<br> Image from our chatgpt plugin retrieving data from the vector database deployed http://3.8.31.17:8000/docs#/default/get_nearest_neighbors

# 4. Build automated decision machines <br>
Forecasting, predictive modelling, advanced analytics. Services you can not find anywhere else.


# 5. Deploy domain specific privately owned AI Models for your Project<br>
Integrate AI models built on your knowledge base to process, analyze, and make predictions based on the available data.<br>

# What we bring to the table:<br>
**AI expertise** combined with our **Architecture and Construction industry Professional Experience**

# Proposed Collaboration:<br>
We propose a collaboration where our team acts as an outsourced AI development arm for your company. In this capacity, we can:<br>
1. Customize the AI Framework: Work closely with you to adapt our AI framework to your specific needs and objectives.
2. Provide Access to Innovative Technology: Grant you access to cutting-edge AI technology that can be integrated into your operations.

### Where we are in our development phase:<br>
1.Our framework is now operational on various cloud providers such as AWS services.<br>
2.We are currently in the phase of testing our APIs.<br>
3.A successful proof of concept has been completed.<br>
4.We are now prepared to transition into production development.<br>

### We are seeking a strategic partnership
We are currently seeking strategic partnerships to boost our growth and discover more uses for our technology.
We foresee that such cooperation will promote joint growth and enable us to adapt our solution to industry-specific requirements.<br><br>

<br><br>

# we-ai framework
**WE-AI framework design**
1. We build versatile APIs that act as a software glue, enabling the creation of varied services.
2. We harness open-source code, tapping into an extensive pool of resources.
3. Our adaptive framework utilizes a technology-agnostic design, capable of integrating various models and tech, evolving in sync with industry advancements.



           +-----------------------------------+
           | OpenAI                            |
           | Open Source Language Models       |
           | we-ai Private Data Models         |
           +-----------------------------------+
                              |
                              v
                  +-----------------------+
                  | we-ai LLM Toolkit     |
                  +-----------------------+
                              |
                              v
                  +-----------------------+
                  | MODELS ROUTER         |
                  +-----------------------+
                              |
                              v
                  +-----------------------+
                  | we-ai API middleware |
                  +-----------------------+
                              |
                              v
        +--------------------+   +-----------------+   +--------------+
        | Document Store     |   | Data Getters    |   | Data Loaders |
        +--------------------+   +-----------------+   +--------------+
                              |
                              v
        +-------------------------------+    +----------------+
        | Meta Index- Question Engines  |    | Services API's |
        +-------------------------------+    +----------------+
        
In this diagram:
1. **AI language technologies:** 
Primarily focusing on Large Language Models, we illustrate the various options accessible via the we-ai API middleware. 
Our offering extends to **enterprise solutions** that include privately operated **open source models**, empowering businesses with a high degree of customization and control over their AI language technologies, and **private data**.

1. The "LLM Toolkit" represents any language model toolkit, which interacts with the "we-ai API middleware "

2. The **we-ai API middleware** acts as a middleman, enabling interaction between the "LLM Toolkit" and various data sources (i.e., "Document Store," "Data Getters," and "Data Loaders").

3. Loading Data from **we-ai** into the API Retrieval System
The **we-ai API middleware** defines an /upsert endpoint for users to load data. This offers a natural integration point with Data Getters hub, which offers over 25 data loaders from various API’s and document formats, with more under development.

4. The data sources **Document Store, Data Getters, Data Loaders**, represent various document storage and retrieval systems that implement the **we-ai API middleware** , allowing them to exchange data with the model.

5. The **Meta Index- Question Engines** has been added under **Document Store**, **Data Getters** and **Data Loaders** These represent the vector indices built over any data stored in their respective document stores.

This high-level architecture allows any LLM to access data from various sources seamlessly, provided these sources implement the API. The we-ai API essentially standardizes how these systems interact, making it easier for developers to integrate and manipulate a wide range of data.


