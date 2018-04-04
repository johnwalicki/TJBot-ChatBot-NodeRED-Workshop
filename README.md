# TJBot-ChatBot-NodeRED-Workshop
Chatbot Workshop using a TJBot and Node-RED - This workshop is a fast paced 60 minute session on how to use Node-RED to construct a Chatbot using IBM Cloud Watson Cognitive microservices.

# TJBot ChatBot Workshop Agenda
* Introduction to Node-RED and TJBot
* Introduction to Watson Cognitive Services - Speech to Text / Text to Speech / Language Translation / Watson Conversation
* Build a Text to Speech flow using Node-RED
* Build a Speech to Text flow using Node-RED
* Build a Language Translation flow using Node-RED
* Build a Conversation flow using Node-RED
* ChatBot Finale !

## Introduction to Node-RED and TJBot
* Node-RED is an open-source Node.js application that provides a visual programming editor that makes it easy to wire together flows. Node-RED embodies a low-code style of application development, where developers can quickly create meaningful applications without having to write reams of code. There are a number of benefits to low-code application development, all of which we’ve seen first-hand with Node-RED.

 * It reduces the time it takes to create a working application: This allows the real value to be realized much quicker than with traditional development models.
 * It’s accessible to a wide range of developers and non-developers: This is one of the most important benefits we’ve seen. Anyone who understands a domain-specific problem, such as a business analyst, a linguist, or a building engineer, will know the discrete steps needed to solve it. Node-RED gives them the tools to express those steps within a flow and build the solution for themselves.
 * The visual nature helps users to see their application: “Show, don’t tell” is a powerful concept. We often see Node-RED used to demo API capabilities, such as for Watson cognitive services. It’s so effective because the visualization of your application logic shows the art of the possible without having to explain every semi-colon, bracket, and brace. Not everyone thinks in lines of code; the visual representation of application logic is much more relatable.

* TJBot 
 * Link - https://github.com/ibmtjbot/tjbot/blob/master/README.md

### Connect to your workshop TJBot
* Your laptop needs to be connected to the IBM Wireless network.  If your system is connected to the IBM Visitor network, you will not be able to connect to your TJBot.  Connect your system to the IBM internal network before proceeding.
* Open a browser tab on your laptop - Firefox or Chrome recommended.
* Next to your TJBot, there will be a postcard / Post-IT with the IP Address of your TJBot.
* Enter **http://<your TJBot>:1880**
* Node-RED will load and you can proceed with the rest of the workshop.

## Introduction to Watson Cognitive Services - Speech to Text / Text to Speech / Language Translation / Watson Conversation
* Speech to Text
* Text to Speech
* Language Translation
* Watson Conversation

## Build a Text to Speech flow using Node-RED
0. Create Text to Speech Credentials
 * Visit https://console.bluemix.net/catalog/services/text-to-speech
 * Press the Create button to generate an API key.
 * Paste these details into the Text to Speech node.
 * Double-click to open the Text to Speech node.
 * Enter the username and password credentials
 * Press the Done button
 * Press the Deploy button.
1. Click on the tab connected to the **inject node** to start the flow
2. Double click on the **text to speech** node to change the voice to Allison
3. Double click on the **inject node** to change the sentence

## Build a Speech to Text flow using Node-RED
## Build a Language Translation flow using Node-RED
## Build a Conversation flow using Node-RED
## ChatBot Finale !
