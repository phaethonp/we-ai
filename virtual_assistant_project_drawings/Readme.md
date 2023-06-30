# Semantic search over BIM/IFC files 
The process involves creating a search system that understands the meaning of the queries and the IFC data, rather than just matching keywords.<br>
The topic is an active area of research.<br>
There are two distinct methodologies to tackle this issue, each serving a unique purpose:<br>

The first approach involves the use of a JSON file. Data is extracted from this file and sent along with the prompt to the Language Learning Model (LLM). Calculations are executed by a computation engine and subsequently submitted to the AI model via the prompt. This process ultimately returns Natural Language (NL) results to the user.<br>
1. JSON file --> extract data--> send with the prompt to LLM. Calculations performed by a computation engine and submitted to the ai model through prompt--> return NL results to user<br>

The second approach is Zero-Shot Learning.<BR>

### 2. Zero-Shot Learning

   

The paper discusses the concept of zero-shot information extraction (IE) which seems good enough for our purpose. it does not provide implementation details.<br>
https://arxiv.org/pdf/2304.09333.pdf <br>

we can find more details on Zero-Shot IE here<br>
### Zero-Shot Information Extraction via Chatting with ChatGPT
https://arxiv.org/abs/2302.10205
