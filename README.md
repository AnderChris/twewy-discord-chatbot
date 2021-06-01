# Discord Chatbot: The World Ends With You

This is a Discord AI Chatbot that uses the [Microsoft DialoGPT conversational model](https://huggingface.co/microsoft/DialoGPT-medium) fine-tuned on the game transcript of [The World Ends With You](https://en.wikipedia.org/wiki/The_World_Ends_with_You) (TWEWY).

I trained the model using the lines of my favorite quirky character, Joshua (left in the image below). He has about 700 lines in total in the entire game.

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/gameplay.png" width=400><br>

Here is a demo of the Discord bot in action.

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/discord.gif" width=500><br>

You can also directly chat with the model hosted on [Hugging Face's Model Hub](https://huggingface.co/r3dhummingbird/DialoGPT-medium-joshua).

<img src="https://github.com/RuolinZheng08/twewy-discord-chatbot/blob/main/gif-demo/huggingface.gif" width=400><br>

## Structure of this Project

- `model_train_upload_workflow.ipyb`: Notebook to be run in Google Colab to train and upload the model to Hugging Face's Model Hub
- `discord_bot.py`: Script to be imported into a Repl.it project

## Resource Links

- [My TWEWY dataset on Kaggle](https://www.kaggle.com/ruolinzheng/twewy-game-script)
- [My Hugging Face Model](https://huggingface.co/r3dhummingbird/DialoGPT-medium-joshua)
- [My Repl.it `discord_bot.py` script](https://replit.com/@r3dhummingbird/TWEWY-Discord-Chatbots-HuggingFace#main.py)
