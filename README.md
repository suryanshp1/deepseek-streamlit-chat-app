## DEEPSEEK STREAMLIT OLLAMA APP

a simple deepseek chat application using streamlit

### How to run ?

1. Download ollama in your local server/PC

2. Run command 

```bash
ollama pull deepseek-r1 # pull model

ollama run deepseek-r1 # run model in CLI

ollama list # list all models
```

3. Create conda env

```bash
conda create -p venv python==3.11 -y
```

4. Activate the env

```bash
conda activate ./venv
```

5. Install required packages

```bash
pip install -r requirements.txt
```

6. Run application

```bash
streamlit run app.py
```


Screenshot


![Screenshot 1](https://raw.githubusercontent.com/suryanshp1/deepseek-streamlit-chat-app/refs/heads/main/deepseek.png)
