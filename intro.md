# we-ai 
A framework for building public services and  Enterprise solutions that respect private data. We build on open-source code

## Use cases

### Property development: Enterprise solutiom
https://primeshare.app/section_4 <br>

### Solutions:
**Connect Your Project to AI;** Your AI Managing Agent and Services platform<br>
Our team is developing a solution to link every property development to AI-Platform. What you get:<br><br>
**1. a Communications Hub:** Streamline communications, messages, and emails.<br>
Accessreal-time AI-generated insights and recommendations.<br>
**2. Discover data. Build a knowledge base**<br><br>
Gather, organize, and structure data to create a comprehensive knowledge base.<br>
**3. Deploy domain specific AI Models for your Project**<br><br>
Integrate AI models built on your knowledge base to process, analyze, and make predictions based on the available data.

**What we bring on the table:**<br>
**AI expertise** combined with our **Architecture and Construction industry knowledge** can pave the way for groundbreaking advancements in property development.

**Proposed Collaboration:**<br>
We propose a collaboration where our team acts as an outsourced AI development arm for your company. In this capacity, we can:<br>
1. Customize the AI Framework: Work closely with you to adapt our AI framework to your specific needs and objectives.
2. Provide Access to Innovative Technology: Grant you access to cutting-edge AI technology that can be integrated into your operations.

<br><br>
### Listen to the People: Public Service solution

https://medium.com/p/242cbb0de7fc<br>
Communication Platform as a Service (CPaaS)— Revolution in political engagement and Understanding

*Our platform redefines political engagement, creating a digital space where citizens interact asynchronously with their representatives. Using advanced AI, we transform these citizen voices into actionable insights, allowing political entities to accurately meet constituents’ needs.” — **People-Centric Technologies Powered by AI**<br><br>
The critical distinction is that this service not only collects and manages constituent data, but also uses advanced AI technology to analyze this data and transform it into actionable insights. These insights can help inform campaign strategies, policy decisions, and targeted communications to better meet constituents’ needs and preferences.<br><br>

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


