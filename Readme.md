### RAG Implementation with Qdrant vector database.

#############################################
Command to run:
1. docker info
2. docker pull qdrant/qdrant 
3. docker run -p 6333:6333 -v .:/qdrant/storage qdrant/qdrant


############################################################
Then open the terminal in pwd:
python -m venv .venv 
cd .venv 
cd scripts 
./activate
cd ..
cd ..
pip install -r requirements.txt

###########################################################

Now, 
run the ingest.py to create the embeddings. Once the embeddings are created,
run the app.py to retrieve the relevant docs/chunks