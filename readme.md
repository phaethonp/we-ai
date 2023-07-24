# APIs for Property Development
In essence, WE-AI is the Siri for multiplayer communication on a Property Development platform.
WE-AI is a virtual assistant that uses project data to interpret and respond to user requests. It's specifically designed to facilitate communication among users in the property development industry. Think of it as Siri, but with a focus on distributing relevant information to architects, contractors, and investors at the right time, ensuring effective communication and coordination.<br>

<p align="center">
  :large_blue_circle:
</p>


### The new context created by Generative AI
Large Language Models are a phenomenal technology that will reshape the property development industry, from the investment decision stage down to daily construction site operations<br>

We are creating a comprehensive toolkit to glue together legacy technologies with Generative AI and address inherent challenges of the property development industry<br>
We see a potential for Generative AI to address challenges at the following levels:<br>

:small_blue_diamond: Decision Making and Pre-Investment Phase: `Climate Change Solutions` `ESG compliance`<br>
:small_blue_diamond: Design and pre-construction stage:  

:small_blue_diamond: Construction and project management: `Friction` `Lack of Data` `Uneven Information Distribution` `Safety` `Low Productivity` <br>
The **property development industry** is marked by **inherent challenges**, such as **friction** between parties due to **uneven information distribution, safety concerns**, issues related to **quality**, and **low productivity.**<br>
By connecting the myriad of stakeholders involved in property development processes via streamlined information sharing, we can mitigate these fragmented procedures. <br>



<p align="center">
  :large_blue_circle:
</p>

# Building on the OpenAI ChatGPT Retrieval Plugin API
OpenAI's ChatGPT Retrieval Plugin offers a standardized API specification, enabling document storage systems and document retrieval services to interface not only with ChatGPT, but also with any Large Language Model (LLM) toolkit that utilizes a retrieval service.<br>
WE-AI leverages this by providing a range of integrations with the ChatGPT Retrieval Plugin API, thereby creating an interconnected ecosystem of native AI services.<be>

<br>
Key features of WE-AI include:<br>

* The development of versatile APIs that serve as 'software glue', bridging the gap * between legacy systems and AI.<br>
The utilization of open-source code, capitalizing on a vast pool of resources.<br>
* A technology-agnostic design that allows for the integration of various models and technologies, ensuring adaptability to industry advancements.<br>

<p align="center">
  :large_blue_circle:
</p>

# Key components of the framework


## 1. Connecting Data Sources to Our AI Engine
Integrate Your Data Sources with Our AI Engine: **Unlock** the potential of **untouched data reservoirs**. Transform every piece of information into a valuable data source. Accumulate, order, and systematize data to construct an all-encompassing knowledge base.<br><br>
<img width="624" alt="Screenshot 2023-06-15 at 22 28 19" src="https://github.com/phaethonp/we-ai/assets/33053426/058b2632-22b6-4c07-81bd-841ee92fc43a">
<br><br>
## 2. Create AI Data Warehouse from Raw, Structured, or Unstructured data 
Harness the power of our AI framework to establish a unified source of information. <br>

<img width="1208" alt="Screenshot 2023-06-15 at 22 52 56" src="https://github.com/phaethonp/we-ai/assets/33053426/f3feb841-b4f9-41b2-8867-bc2bcc09e714"><br><br>
## 3. Query unstructured data with natural language

<img width="1024" alt="Screenshot 2023-06-15 at 23 43 13" src="https://github.com/phaethonp/we-ai/assets/33053426/12df28b9-036c-43ad-8e31-074bc4669bac">
<br> Image from our chatgpt plugin retrieving data from the vector database deployed http://3.8.31.17:8000/docs#/default/get_nearest_neighbors
<br><br><br>

## 4. Run powerful applications over your data <br>
Get Services you can not find anywhere else:<br>
**AI-Powered Collaboration Platform:** Enhances stakeholder communication, reducing friction and improving project transparency.<br>
<br>
**Data Aggregation and Visualization:** Captures, aggregates, and presents project data comprehensively.<br>

**Intelligent Information Distribution System:** Distributes relevant information to stakeholders at the right time.<br>

**AI-Driven Safety Monitoring and Alert System:** Monitors site safety continuously, providing real-time alerts.<br>

**Predictive Productivity Analytics:** Analyzes historical data to identify and eliminate productivity bottlenecks.
<br><br>


## 5. Access Domain-Specific, Privately-Owned AI Models Tailored for the Property Development Industry <br>
The transition to deploying fine-tuned, domain-specific, privately-owned AI models tailored for your organization is important and necessary for several reasons:<br>

**Customization:** These models are specifically designed to address your organization's unique needs, challenges, and goals. They can therefore provide solutions that are much more relevant and effective compared to generic, one-size-fits-all AI models.
<br>
**Data Security:** Privately-owned AI models allow you to maintain complete control over your data, which is essential for complying with data privacy regulations and protecting sensitive information.
<br>
**Scalability:** As your organization grows, so too can your AI models. They can be designed to scale with your needs, ensuring you always have the right level of AI power at your disposal.


<p align="center">
  :large_blue_circle:
</p>



# The WE-AI Framework
**WE-AI Framework Design**
1. We build versatile APIs that act as `software glue`, enabling the creation of varied services.
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
We focus primarily on Large Language Models, showcasing the various options accessible via the we-ai API middleware. 
Our offering extends to **enterprise solutions** that include privately operated **open source models**, empowering businesses with a high degree of customization and control over their AI language technologies, and **private data**.

1. The "LLM Toolkit" represents any language model toolkit, which interacts with the "we-ai API middleware "

2. The **WE-API API Middleware** acts as a middleman, enabling interaction between the "LLM Toolkit" and various data sources (i.e., "Document Store," "Data Getters," and "Data Loaders").

3. Loading Data from **we-ai** into the API Retrieval System
The **WE-API API Middleware** defines an /upsert endpoint for users to load data. This offers a natural integration point with Data Getters hub, which offers over 25 data loaders from various API’s and document formats, with more under development.

4. The data sources **Document Store, Data Getters, Data Loaders**, represent various document storage and retrieval systems that implement the **WE-API API Middleware** , allowing them to exchange data with the model.

5. The **Meta Index- Question Engines** has been added under **Document Store**, **Data Getters** and **Data Loaders** These represent the vector indices built over any data stored in their respective document stores.

This high-level architecture allows any LLM to access data from various sources seamlessly, provided these sources implement the API. The we-ai API essentially standardizes how these systems interact, making it easier for developers to integrate and manipulate a wide range of data.
