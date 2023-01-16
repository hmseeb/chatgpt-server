# API server for ChatGPT

Backend server for **ChatGPT With Voice**. You can check out [the website](hmseeb.github.io/chatgpt), or find the [frontend repo](https://github.com/hmseeb/chatgpt) on GitHub.

## Installation
Clone this repo.

```bash
git clone https://github.com/hmseeb/chatgpt-server.git
```

Prepare environment variables by creating `.env` at the project root. You need to sign up for an OpenAI account [here](https://openai.com/api/), using email and password.

```t
PORT=8000 # Or whichever port available
OPENAI_EMAIL="<your-openai-email>"
OPENAI_PASSWORD="<your-openai-password>"
```

```bash
npm install
npm run build
npm run start
```
