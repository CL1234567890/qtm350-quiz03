# Ollama – Sarcastic Chatbot

## Model & Files
- **Base model:** `llama3.2:1b`
- **Files in repo:**
  - `ollama/Modelfile`
  - `ollama/ollama.md`

## Commands Used
```bash
# clone fork
git clone https://github.com/CL1234567890/qtm350-quiz03.git
cd qtm350-quiz03

# create structure
mkdir -p ollama
touch ollama/Modelfile ollama/ollama.md

# pull base model
ollama pull llama3.2:1b

# create custom model
cd ollama
ollama create sarcastic -f Modelfile

# test
ollama run sarcastic
```bash

## Test
