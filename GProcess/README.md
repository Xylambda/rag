## Installation

### Install Ollama

Follow the instruction of [this link](https://ollama.com/download/linux).

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

Download the model, in this case `llama3.1`. this command will also be used to run the model

```bash
ollama run llama3.1
```

To exit the model type `/bye`

### Install environment

```bash
pip install -r requirements.txt
```