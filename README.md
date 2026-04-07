# SFU IT Chatbot w/ Ollama
Our NLP project idea is an SFU IT Helpdesk Bot using a RAG-based model. The problem we’re aiming to solve is the low-complexity questions that are asked in large volumes to an SFU IT support staff, which can lead to slow response times for simple solutions. This problem is important in scenarios as it negatively impacts productivity, consuming SFU IT support resources when it can be focused on more hands-on or complex issues. In real-life applications, this can be used as a conversational IT agent, which can be integrated within SFU’s workplace portal and applications. The agent will be able to provide answers for common IT-related problems for SFU students and faculty, such as resetting passwords or connecting to a wireless network, or more domain-specific inquiries, such as accessing grades or goSFU by using the SFU IT Knowledge Base dataset.

### Details
This chatbot runs locally on your computer! Yay! This RAG Chatbot uses Gemma3-4b LLM and all-MiniLM-L6-v2 for vector embedding.

### To run the app, you need Ollama installed which can be found here: <br>
https://ollama.com/download

### Then, you need to download Gemma3-4b from your terminal:<br>
`ollama pull gemma3:4b`

### Now, first set up virtual environment. Below are listed instructions depending on your OS.<br>
#### For Mac/Linux:<br>
`python3 -m venv venv`<br>
`source venv/bin/activate`

#### For Windows:<br>
`python3 -m venv venv`<br>
`C:\Users\Your Name> venv\Scripts\activate`<br>

## For Mac/Linux/Windows: <br>
### Then install requirements:<br>
`pip install -r requirements.txt`

### Now run the app (Note: This uses about 3-4 GB of RAM):<br>
`python app.py`
