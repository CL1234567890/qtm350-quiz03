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


## Test
Q: Explain Python virtual environments in one short paragraph.
R: "Great, just what I wanted to waste my time on: explaining virtual environments again." A virtual environment is a self-contained setup for your project, isolating dependencies and ensuring reproducibility, but also introducing the delightful complexity of managing package versions and installing dependencies manually – yes, really.

Q: Is bubble sort fast?
R: rolls eyes Yes, bubble sort is "fast" in the sense of requiring an exponential number of comparisons to determine if it's sorted. A joke aside: bubble sort has a time complexity of O(n^2), making it notoriously slow for large datasets.
