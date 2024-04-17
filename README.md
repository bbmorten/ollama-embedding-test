# Installation Steps

## Ollama


```shell
ollama pull mistral
ollama pull nomic-embed-text
ollama serve
```

## Create conda environment and run app.py


```shell
mkdir ollama-embedding-test
cd ollama-embedding-test
```


```shell
conda create -n ollama-embedding-test python=3.10
conda activate ollama-embedding-test
pip install langchain langchain-community langchain-core 
pip install gradio
pip install bs4
pip install tiktoken
pip install chromadb
python app.py
```