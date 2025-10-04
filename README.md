# Task5
It is a multi-tool AI assistant . Read  README for more information. 
🤖 Smart AI Assistant (Task 5)
This project is developed as Task 5 of the AI assignment.
It is a multi-tool AI assistant that can answer questions using:

GlobalMart RAG → Internal product & policy knowledge (via FAISS + SentenceTransformers)
Calculator → For solving math expressions
Wikipedia → For general knowledge queries
Google Gemini LLM → Works as a planner & synthesizer to decide which tool(s) to use and then generate the final natural answer
🔑 Why do we need API Keys?
This project uses Google Gemini API for:

Splitting user queries into parts (Planner)
Selecting the right tool (RAG, Calculator, or Wikipedia)
Generating the final human-like answer (Synthesizer)
👉 Without the Gemini API key, the system cannot plan or synthesize responses.
The RAG, Calculator, and Wikipedia work as tools, but Gemini is the brain that combines them.
git clone https://github.com/SA12352.git
cd Task5
