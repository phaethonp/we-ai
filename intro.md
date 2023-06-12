# we-ai 
A framework for building services over private data

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


