mini-rag
This is a minimal implementation of the RAG model for question answering.

Requirements
* Python 3.8 or later
* Install Python using MiniConda
  * Download and install MiniConda from here: https://docs.conda.io/en/latest/miniconda.html
* Create a new environment using the following command:
  ```bash
  conda create -n mini-rag python=3.10conda create -n mini-rag python=3.10
 conda activate mini-rag

 pip install -r requirements.txt
 cd docker
cp .env.example .env

uvicorn main:app --reload --host 0.0.0.0 --port 5000