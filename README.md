\# NoteMind – Chat With Your Notes Using AI



NoteMind is an AI-powered PDF Question Answering application that allows users to upload PDF documents and ask questions based on their content.



\## Features

\- Upload and read PDF documents.

\- Extract text from PDFs.

\- Split extracted text into smaller chunks.

\- Generate embeddings using Sentence Transformers.

\- Store and search document vectors using FAISS.

\- Generate contextual answers using the Groq API.

\- Streamlit-based user interface.

\- PostgreSQL service configured through Docker Compose.



\## Technology Stack

\- Python 3.11

\- Streamlit

\- PyPDF

\- Sentence Transformers

\- FAISS

\- Groq API

\- PostgreSQL

\- Docker and Docker Compose

\- Git and GitHub

\- GitHub Actions

\- Render



\## Project Architecture



PDF Upload → Text Extraction → Text Chunking → Embeddings → FAISS Vector Search → Relevant Context Retrieval → Groq LLM → Generated Answer



\## Project Setup



1\. Clone the repository:



&#x20;  `git clone https://github.com/Amanc0de/NoteMind.git`



2\. Open the project directory:



&#x20;  `cd NoteMind`



3\. Install dependencies:



&#x20;  `pip install -r requirement.txt`



4\. Create a `.env` file and add your Groq API key:



&#x20;  `GROQ\_API\_KEY=your\_api\_key`



5\. Run the application:



&#x20;  `streamlit run app.py`



\## Docker Setup



Build and start the services:



`docker compose up --build`



Open the application at:



`http://localhost:8501`



\## Deployment



Live Application: https://notemind-vnys.onrender.com



GitHub Repository: https://github.com/Amanc0de/NoteMind



\## CI Workflow



GitHub Actions runs automated Python syntax validation and Docker image build checks when changes are pushed or pull requests are created.



\## Author



Aman Yadav  

B.Tech – Computer Science and Engineering (Data Science)  

NIET Greater Noida

