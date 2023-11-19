# Title

Custom Chatbot Langchain (FREE)

<a href="https://play.google.com/store/apps/details?id=com.gitpoint">
    <img alt="Get it on Google Play" title="Google Play" src="http://i.imgur.com/mtGRPuM.png" width="140">
</a>

[![Alt text](https://img.youtube.com/vi/PB7w9zhs9XM/0.jpg)](https://www.youtube.com/watch?v=PB7w9zhs9XM)

# Description

Make a bot that answers question from your txt file. Human like responses, and accurate using the llama 7B. Everything in this is free.
I have added a short txt file that has some few stuffs about the university of Iceland, and can answer few questions based on that txt file.

## Installation
1. **Clone Repository:**
    ```bash
    git clone https://github.com/Cyboghostginx/Custom-Chatbot-Langchain-FREE-.git
    cd Custom-Chatbot-Langchain-FREE-
    ```

2. **Ollama Installation:**
    ```bash
    curl https://ollama.ai/install.sh | sh
    ollama run llama2
    ```

3. **Langchain Installation:**
    ```bash
    pip install git+https://github.com/langchain-ai/langchain.git@8d6faf56657070137a16669bc2420a08a5ab7f24#subdirectory=libs/langchain
    ```

4. **Tiktoken Installation:**
    ```bash
    pip install tiktoken
    ```

5. **FastEmbed Installation:**
    ```bash
    pip install fastembed
    ```

6. **Qdrant-Client Installation:**
    ```bash
    pip install qdrant-client
    ```

## Usage

```bash
python bot.py
```

## Tested

I used a macbook pro m1, 16gb ram for this.

Splitting tx into chunks - Almost instantly<br>
Embedding finished in 1.6 seconds<br>
Similarity search - Almost instantly<br>
Chat model response - 20 seconds for the the llama 7b model.<br>

Note that when this is hosted on a better gpu, the chat model to would respond almost immediately.
Thanks!
