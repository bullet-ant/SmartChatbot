# Intelligent Customer Help Desk with Smart Document Understanding 🤖

In this project a chatbot is created which offers a complete and easy way to answer different sets of questions asked by the customers. With the help of Watson discovery channel it can also answer some typical questions about the operation of a device because we have feeds the owners manual to the watson discovery channel. The benefits of this kind of chatbot is that it is superior than the typical chatbot which can answers simple questions like store location and hours. The chatbot is upgraded with the help of watson discovery collection which is build using smart document understanding.


### Pre-requisites

* Node-RED
* IBM Watson Assistant
* IBM Cloud Services
* IBM Watson Discovery


### Installing

To get the application up and running follow the below steps:

* Create a chatbot using Watson Assistant.
* Use Watson Discovery to  redirect the user's query to the section of the owner's manual.
* Use Node Red to wire together Api and online services.
* Integrating it with IBM Cloud.


## Flow

![alt text](https://camo.githubusercontent.com/4649f9c52c831e3decbb31d7f919926567d8d16e/687474703a2f2f692e78702e696f2f7457537055466c2e706e67)


## What will you get to know here?


1. How to [create a skill](skill.md) using Watson Assistant.


2. How to [create UI](flow.md) with node red flow (Chatbot).


3. How to [create cloud function](Cf.md) using IBM cloud.


4. How to [connect Watson discovery](Discovery.md) to chatbot through Cloud funtcion.


## Built With

* [Node-RED](https://nodered.org/docs/) - Developing the dashboard
* [IBM Watson Assistant](https://www.ibm.com/cloud/watson-assistant/) - Configuring intents and dialogues.
* [IBM Watson Discovery](https://www.ibm.com/cloud/watson-discovery) - Used to find the corresponding section in the manual.
* [Cloud Functions](https://www.ibm.com/cloud/functions) - For retrieving the results created by IBM Watson Discovery.


## Author

* **Aman Kumar** - [bullet-ant](https://github.com/bullet-ant)


## License

This project is licensed under the MIT License
