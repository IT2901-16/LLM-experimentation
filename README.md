# Llama2-Powered Chatbot for PDF's

## Installation Instructions

Requires python >3.9

1. Download the Llama 2 model [here](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q2_K.bin)

2. Create a models directory and place the model there.

3. Create a virtual environment and enter it  
```bash
python -m venv .venv
```  
```bash
source .venv/bin/activate
```

4. Install the dependencies with the command:  
```bash
pip install -r requirements.txt
```

5. Create a data directory and place pdf files in it. 

6. Create the vector store
```bash
python create_vector_store.py
```

7. Run the Streamlit web app with the command:  
```bash
streamlit run app.py
```


credit: https://github.com/anair123/Llama2-Powered-QA-Chatbot-For-Research-Papers