# AI Topic Specific Chatbot

This repository has all the code required to create a working, topic specific chatbot. This repository will allow you to easily simulate a conversation between two individuals that is based on a topic of your choice. 

The backbone of the Generative Chatbot is the DialoGPT model, that can be found here -https://github.com/microsoft/DialoGPT- . 

# How to use

- Generative_Chatbot
	- This is the code that will generate a conversation between two individuals. Simply 		open the file in google colab and upload the two files also included in the repository,  gameofthrones.ann and gameofthrones_relevent.txt, and you have a chatbot that will talk about game of thrones.
	-  If you want to make the chatbot talk about other topics then you need to create your own CHOSEN_TOPIC.ann and CHOSEN_TOPIC_relevent.txt using the second code file in the repository --> Releventer.

- Releventer 	
	- This code creates the CHOSEN_TOPIC.ann and CHOSEN_TOPIC_relevent.txt, which  are used in the Generative_Chatbot code to create relevant and topic related conversation  (hence the name Releventer).
	- To create the two required files, run all the code and replace the the word "dog" in the final cell, with whatever subreddit topic you want, and it will proceeded to scrape the selected subreddit and then "Releventise" the scrapped comments to ensure a more precise and refined collection of text is fed into the generative chatbot. 

	# Examples
![An example of a minecraft conversation](https://photos.app.goo.gl/qPJF3PnTkXE5TM6WA)

![An example of a game of thrones conversation](https://photos.app.goo.gl/M1EjYuspy4X9efC17)





