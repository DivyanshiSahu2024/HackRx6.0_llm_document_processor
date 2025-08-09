\# 🧠 LLM Document Processing System



This project is built for a hackathon. It uses Large Language Models (LLMs) to process user queries and extract relevant information from unstructured insurance policy documents.



---



\## 🔍 Problem Statement



Given a query like:



> "46-year-old male, knee surgery in Pune, 3-month-old insurance policy"



The system will:



1\. Parse the query

2\. Search policy documents using semantic similarity

3\. Apply insurance logic

4\. Return a decision in structured JSON format



---



\## ⚙️ Features



\- Query parsing using LLMs

\- PDF document loader and chunker

\- Embedding \& semantic search using FAISS

\- Decision engine powered by GPT

\- REST API built with FastAPI



---



\## 🚀 How to Run



\### 1. Clone the repository



```bash

git clone <your-repo-url>

cd llm-document-assistant



\### 2. Install dependencies

```bash

pip install -r requirements.txt



\### 3. Set your API key

Create a .env file in the root:

```env

OPENAI\_API\_KEY=sk-xxxxxxxxxxxxxxxxxxxx



\### 4. Start the server

```bash

uvicorn app.main:app --reload





Visit: http://localhost:8000/docs





\### Sample Query

```json

"46-year-old male, knee surgery, 3-month policy"



\### Folder Structure

``` bash

llm-document-assistant/

├── app/

├── data/

├── embeddings/

├── requirements.txt

├── README.md

├── .env







\###Team

-Divyanshi Sahu



-Garima Mittal

-Ananya Garg

```yaml



---



\### ✅ Step 5: Save the file



Click \*\*File → Save\*\* and close the editor.



---



