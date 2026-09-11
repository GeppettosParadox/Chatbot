# Python Voice Assistant / Chatbot Prototype

An experimental Python project exploring a desktop voice assistant and a small intent-classification chatbot. The repository combines speech recognition, text-to-speech, utility integrations, and a simple Keras/NLTK training pipeline.

I built this as a learning project while exploring conversational interfaces and assistant-style workflows. It is not something I would position as production AI infrastructure today, but it does show some of the earlier hands-on work that led into the automation and AI systems I work with now.

## What the project includes

- Speech-to-text input with `speech_recognition`
- Text-to-speech output with `pyttsx3`
- Voice-driven commands for local desktop utilities
- Integrations for web search, Wikipedia, YouTube, weather, news, jokes, and other external services
- Intent data stored in JSON
- Tokenization and lemmatization with NLTK
- Bag-of-words feature generation
- A small Keras neural network for intent classification
- Saved model and preprocessing artifacts

## Project structure

- `main.py` — voice-assistant command loop and user interaction
- `functions/` — online and operating-system helper functions
- `training.py` — preprocessing and neural-network training pipeline
- `chatbot.py` — chatbot inference logic
- `intents.json` — sample intent definitions
- `chatbot_model.model/` and `chatbotmobdel.h5` — saved model artifacts from experimentation

## Notes

This repository is historical/experimental work. Some dependencies and APIs may be outdated, and a few implementation choices reflect the learning goals of the project rather than how I would structure a production assistant today.

The part I still find useful is the progression of ideas: taking user input, normalizing it, mapping it to an intent or action, and wiring that into a set of tools. That same basic problem shows up in much more capable agent and automation systems today.
