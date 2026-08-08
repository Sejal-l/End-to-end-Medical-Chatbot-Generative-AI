# End-to-end-Medical-Chatbot-Generative-AI

# How to Run?

### STEPS:

Clone the repository

```bash
Project repo: https://github.com
```,

### STEP 01 - Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.11 -y
```

### STEP 02 - Activate the conda environment

```bash
conda activate medibot
```

### STEP 03 - Install the requirements

```bash
pip install -r requirements.txt
```
#run the following command to store embeddings to pinecore
```bash
Python store_index.py
```

#finally run the following command
```bash
Python app.py
```

###Techstack Used
-Python
-LangChain
-Flask
-Pinecone
-Google gemini 2.5