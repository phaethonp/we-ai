# Semantic search over BIM/IFC files 
The process involves creating a search system that understands the meaning of the queries and the IFC data, rather than just matching keywords.<br>
The topic is an active area of research.<br>
2 methods to approach the issue eachcan serve different purpose<BR>
1. JSON file --> extract data--> send with the prompt to LLM. Calculations performed by a computation engine and submitted to the ai model through prompt--> return NL results to user<br>
2. Zero-Shot Learning

   

The paper discusses the concept of zero-shot information extraction (IE) which seems good enough for our purpose. it does not provide implementation details.<br>
https://arxiv.org/pdf/2304.09333.pdf <br>

we can find more details on Zero-Shot IE here<br>
### Zero-Shot Information Extraction via Chatting with ChatGPT
https://arxiv.org/abs/2302.10205
