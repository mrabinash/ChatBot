# ChatBot
The agent handles requests about transfers, balances and credit card payment due dates.
# Building a Banking Chatbot in Google Dialogflow
Link: https://bot.dialogflow.com/6fbc1ece-d4e2-4eae-876b-fc26cc510446
# Introduction
Dialogflow is a Google-owned framework that enables users to develop human-computer interaction technologies that can support Natural Language Processing (NLP). Basically, it lets you make Digital Programs that interact with end users through natural languages. Therefore, we could even say that Dialogflow enables the creation of Conversational User Experience Platforms (CUXP).
# Procedures
## Text/Voice
These are the modes used to communicate the input or the output. The user interacts with the bot through text or through voice. Text would be anything that is typed into the chatbot window and voice would be any message spoken into the chatbot window.
## Agent
An agent is merely another term used to refer to the chatbot. This means giving our chatbot a name. ‘Agent’ refers to the processing module within the application that enables discussions with the chatbot. And sometimes, it is another way to refer to the bot since it functions ‘like a support agent’. The context will always be clear enough for us to know what they mean.
## Expressions
Expressions/Training Phrases are the dialogues/ utterances that we say when they interact with a bot. They represent a user’s desire and are often in the form of a question.

![image](https://user-images.githubusercontent.com/107429918/196221062-e9d21422-52a2-49bc-a8d6-b0d05776533e.png)

## Intent
‘Intents’ are how a chatbot understands Expressions. It is the simple process of grouping expressions into their one meaning, thereby making it easier to program. By using Intents, we don’t have to teach your chatbot how to respond to every Expression. Instead, we can just categorise Expressions into Intents that the bot can easily tackle. It is a lot simpler for both the developer and the chatbot this way. Ultimately, Intents determine the bot’s responses. The most accurate responses occur when a proper range of expressions have been correctly grouped into Intents. Accurate and simple responses are important traits for a good chatbot.

![image](https://user-images.githubusercontent.com/107429918/196228525-7fd1799f-eab0-4efa-ab3a-c5feda17acb8.png)

 ## Entities
‘Entities’ are Dialogflow’s mechanism for identifying and extracting useful data from natural language inputs. Entities helps us to extract specific pieces of information from the users. This can be anything from appointment dates to bank account types or transfer types. Basically, if there is any important data we want to get from the user, we will use a corresponding entity.

![image](https://user-images.githubusercontent.com/107429918/196228572-16ece18d-6513-4997-93d8-cd56d6353565.png)

## Actions & Parameters
These are Dialogflow mechanisms. They serve as a method to identify/annotate the keywords/values in the training phrases by connecting them with Entities. They also provide the prompts that extract information from the user. Actions allow the developer to work with code. And the work will be annotated by Dialogflow. It will recognise and link keywords/values between Parameters, Expressions and Entities.

![image](https://user-images.githubusercontent.com/107429918/196238358-0d666ae5-ed1f-436f-8419-8eb7d6ab58af.png)

# Integration
Actual chatbot deployment on platforms, like websites, etc. is a complicated procedure that requires publishing the bot. But we can still get an idea of how the chatbot would appear when functional. Here’s how:
1.	Navigating to the ‘Integration’ section in the left column.
2.	Toggle ‘Web Demo’ On, then click it to enter.
3.	Enable it and click on the URL.

Here are some demos of my Banking Chatbot WebView screenshots are attached below.

![image](https://user-images.githubusercontent.com/107429918/196230520-511a3cd4-e964-4ce9-a5b1-d21e59460d2a.png)

Opening a bank account.                        

![image](https://user-images.githubusercontent.com/107429918/196238875-b0bacc17-2bcd-4ca3-b8a5-eac1e64e7158.png)

Checking balance.

![image](https://user-images.githubusercontent.com/107429918/196238916-33e372fe-eec0-4964-bf10-da6689a1b83c.png)

Transferring money.                      

![image](https://user-images.githubusercontent.com/107429918/196239053-7d9f945b-6198-4516-a2b4-d692d7a0824d.png)

Processing transaction successfully.


Checking due date of my Credit Card.


General Conversations.
                                                              
# Conclusion
Dialogflow framework can be used to train our chatbot which the user will ask in different ways. So, it is important to keep training the chatbot to improve its accuracy, fix errors and accommodate fallbacks. It is a smart bot in itself, which uses machine learning to improve itself. It constantly learns based on its interactions & training.

I chose Banking Chatbot because it
1.	Pushes Important Information to the user.
2.	can Answer Queries very easily.
3.	can Save Time.
4.	Builds Economy.
5.	can Automate Tasks.
6.	24/7 Support, Interactions available everywhere at any time.


## Google Dialogflow Link:
https://bot.dialogflow.com/6fbc1ece-d4e2-4eae-876b-fc26cc510446

## GitHub Link:
https://github.com/mrabinash/ChatBot
