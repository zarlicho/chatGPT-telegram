# chatGPT-telegram



chatGPT-telegram is a telegram chatbot based on chatGPT from openai which is very powerful




## Installation

install the required libraries






See the [OpenAI API docs.](https://beta.openai.com/docs/api-reference?lang=python)


```bash
pip install -r requirements.txt
```

The library needs to be configured with your account's secret key which is available on the [Website](https://beta.openai.com/account/api-keys).

add your secret key at 

```bash
import openai
openai.api_key = "secret key"
```

to get the telegram secret key you can see the tutorial [here](https://www.pragnakalp.com/create-telegram-bot-using-python-tutorial-with-examples/).

add your telegram secret key at 

```bash
api = 'bot-key'
bot = telebot.TeleBot(api)
```


## Run Locally

Clone the project

```bash
  git clone https://github.com/zarlicho/chatGPT-telegram.git
```

Go to the project directory

```bash
  cd chatGPT-telegram
```

Start the program

```bash
  python main.py
```


