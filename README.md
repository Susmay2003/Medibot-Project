# Medibot-Project

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/Susmay2003/Medibot-Project.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.11 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & Groq credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GROQ_API_KEY="xxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GROQ
- Pinecone
