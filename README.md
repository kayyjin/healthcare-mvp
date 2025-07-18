# Seasonal Flu Chatbot

## Project Overview
This is a local, AI-powered chatbot designed to provide reliable and evidence-based information on seasonal flu prevention. Built using **AnythingLLM** and powered by a local **Ollama** language model (Mistral), the chatbot assists users in Nova Scotia with:

- Understanding the importance of getting an annual flu shot
- Learning practical steps to reduce flu transmission at home and in the community
- Accessing trustworthy public health guidance without needing to search multiple sources

All information is sourced from Canadian public health authorities (e.g., **Nova Scotia Health**, **Government of Canada**, **WHO**) and is intended strictly for **public education purposes** — not for diagnosis or treatment.

---

## Local Deployment & Testing Instructions

### Prerequisites
- macOS 
- [Ollama](https://ollama.com/) installed and running locally (with `mistral` model)
- [AnythingLLM](https://docs.anythingllm.com/)  (Mac App version) is installed and runs as a standalone desktop application.

### Setup Steps
1. **Start Ollama** and load a supported model:
   ```bash
   ollama run mistral
2. Launch the AnythingLLM desktop application 

3. Create a workspace (e.g., “Flu Chatbot”)

4. Upload documents from /knowledge_base/ and ingest them

5. Configure the system prompt using SystemPrompt.txt

6. Ask scenario questions such as:

“How can I reduce my chances of catching the flu this season?”

“If someone at home has the flu, what should I do to avoid getting sick?”

##Disclaimer
This chatbot does not provide medical advice, and cannot diagnose or treat any health conditions.
It is intended for public education purposes only.
For personal medical questions, users should contact a healthcare provider or call 811 in Nova Scotia.
In emergencies, call 911.

##Author
Xishan Jin
Date: July 18th, 2025
