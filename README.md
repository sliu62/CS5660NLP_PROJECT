# CS5660NLP_PROJECT

**Instruction**

The following Python Libraries are required for running the project:

**discord.api**

**openai**

**python-dotenv**

**requests**

Upon installing all the libraries, go under **\CS5660Bot** and create a **.env** including two variables:

**OPENAI_API_TOKEN=**

**DISCORD_TOKEN=**

Lastly, run **python run.py** to start the program, and your own discord bot should be launched and is waiting for your input.

If you have not created a discord bot, follow the instruction on [ChatGPT Tutorial - Create a Chatbot for Discord with Python](https://www.youtube.com/watch?v=wdgVv4UP08c) from 1:24 to 3:58


** Description **

1.
This model is a fine-tuned version of the OpenAI Davinci based model (one of the old model). We have created a very small test dataset to use as the fine-tuning dataset. According to OpenAI, Curie is cheaper and has strength on sentiment analysis, but since our dataset is very small, fine tuning is still covered by the credit, we decided to use Davinci since is more powerful. 
2.
To access the sentiment analysis, type /judge <Message> -> in the input field and enter, then the Discord api will handle the message and pass it to the OpenAI api to process the message and return a response. Lastly, the Discord api will carry the OpenAI response to the bot and give an output of the sentiment 
3.
Since we did not feed enough data, sometimes the result will not be the actual result we expect, but it shows how fine tuning is powerful by using a good pre-trained model and desired data can have the NLP model run in a way we would like to see 
