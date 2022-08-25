## Emergreen Project
### Chatbots Training Data

During the project lifetime two chatbots services have been developed. To train the chatbots using machine learning algorithms, different types of datasets are required so that the models can learn from the data and perform well when they are used in real-life scenarios.
Different techniques of Natural Language Processing (NLP) can be used during the development process with different types of datasets requirements, involving, generally, the need for text annotations so that such data is usable for machine learning approaches.

Two different chatbots were built during Emergreen project using the framework https://rasa.com/open-source/: 
1) RIA: Recycling Information Assistant

2) SolcEllen: Solar Panels Information Assistant

Trainign data was manually collected from data annotation excercises, generated using data programming techniques, and collected from users interactions.
In this repository, we provide the final dataset used to train the two mentioned AI-powered chatbots. In the folder "Recycling Data" we present 13 files containing different user intents' english training data for RIA chatbot.
In the folder "Green Energy Data" we present the data created and used during the development of SolcEllen chatbot. In this case, data is available in English and Swedish since the chatbot was bilingual. 



### Chatito
#### https://github.com/rodrigopivi/Chatito

During the project, we made use of the tool Chatito to programatically create more training data to satisfy our data needs in our development iterations. The use of this tool proved to be very efficient, specially when trainign the chatbot on complex use cases and entities recognition tasks, such as recycling objects and items, types of bins, addresses, streets, and postal codes, within others.
We provide the data generation rules written in Chatito's domain specific language (DSL) in the folder "Data Programming".



