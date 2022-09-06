# ChatBot

This is an intent based chatbot. The bot is in python and the model parameters are tuning using [keras tuner](https://github.com/keras-team/keras-tuner).

The model is currently trained on a small number of [intents](intents.json).

### [Intents](intents.json)

The intents file is divided into:
1. tags: class name
2. patterns: example of users chat
3. responses: response of the bot

For e.g., 
```
{"intents": [
    {"tag": "greeting",
      "patterns": [
        "Hi",
        "How are you", 
        "Is anyone there?", 
        "Hello", 
        "Good day", 
        "Whats up", 
        "Hey", 
        "greetings",
        "Hi there",
        "Hola",
        "Hello there",
        "Hya",
        "Hya there"],
      "responses": [
        "Hello!", 
        "Good to see you again!", 
        "Hi there, how can I help?"]
    }
}
```
