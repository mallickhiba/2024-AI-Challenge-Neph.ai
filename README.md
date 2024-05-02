Neph.ai aims to tackle the challenge of CKD management in interpreting medical test reports and symptom management by using Generative AI which uses accurate biomedical information to help them interpret their results and allow for easier management of their CKD. 

Pre-trained language model: BioMistral 7B
Embedding Model: PubMedBert
LangChain. Llama CPP
Vector Database: Qdrant

How to run:
1. Have Docker service running
2. In command line, run 'python ingest.py' (allow for libraries to download from requirements.txt)
3. In another terminal run "uvicorn app:app"
4. Access app on localhost:8000 