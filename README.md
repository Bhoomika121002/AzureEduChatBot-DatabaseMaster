# Azure EduDB- ChatBot

## Problem Statement:

Engineering Students get confused alot in studying Database Management System. It is the very Important for the students who belong from the technological background. I have designed a ChatBot which gives all the information about DBMS(Database Management System)."Azure Edu Chatbot: Database Master " is a friendly ChatBot which will give the information about the Database and all the tools and services involved in Database in a Chit - Chat manner which will definitely help students in a more convenient manner to Learn.

## Project Description:

In my project, I made extensive use of Microsoft Azure services to build an educational chatbot that provides details about the Azure database system and its services. Using AI/ML services from Azure, this chatbot was created. QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data.    It is used to find the most suitable response for any input from your personalised knowledge base (KB) of data. Building conversational client applications, such as social media apps, chat bots, and speech-enabled desktop apps, is frequently done with QnA Maker. We can prebuild or upload the questions for our chatbot using Azure QnA Maker. Here, we've used Azure Bot Service to add chatbot to our google site. Websites, apps, email, GroupMe, Facebook Messenger, Kik, Skype, Slack, Microsoft Teams, Telegram, SMS, Twilio, Cortana, and Skype for Business may all incorporate Azure Bot Service. An app always runs in an App Service plan when it is part of the App Service (web, API, or mobile apps). You may utilise Azure Applications to keep an eye on your running applications. Powerful analytics tools are built in to help you identify problems and understand how users actually use your app, and it will instantly detect performance anomalies.  It's designed to help you continuously enhance performance and usability. Consequently, using the aforementioned technologies My chatbot is embedded inside the Google site which I created and explained in it many more Content in an aesthetic manner.  

## Introduction: 

EduDB Chatbot is a simple chatbot for answering all the questions related to Database and the database services used on the Microsoft Azure Platform. Using Azure Cognitive Services provided by Microsoft Azure and website created by using google sites, makes this amazing chatbot unique. All you have to do is simple ask my chatbot what you want to know.

## TECHNOLOGIES USED 

•	Microsoft Azure

I used Microsoft Azure as my main technology in this project. Azure is a platform for cloud computing and an online portal that you may use to access and administer Microsoft's cloud resources and services. Depending on your needs, these services and resources may store and alter your data. All you need is an active internet connection and the ability to connect to the Azure portal in order to access these resources and services. It is free to start using and uses a pay-per-use business model, so you only pay for the services you use.

In this project, I have tried to use these following Azure Cognitive Services into my project:

1.	QnA Maker: QnA Maker is a Natural Language Processing (NLP) cloud service that enables you to add a conversational layer of natural language to your data. It is used to locate the most suitable response for any input from your personalised knowledge base (KB) of data. With the help of this cognitive service, you can quickly create a knowledge base of queries and responses that can serve as the foundation for a conversation between a human and an AI agent.
2.	Knowledge Base: QnA Maker imports your material into a database of questions and answers. A knowledge base is created using a combination of all of these techniques; starting with a base dataset of questions and answers from an existing FAQ document, adding common conversational exchanges from a chit-chat source, and extending the knowledge base with additional manual entries.These questions and answers are editable.
3.	App Service Plan: In App Service (Web Apps, API Apps, or Mobile Apps), an app always runs in an App Service plan. In addition, azure functions  also has the option of running in an App Service plan. An App Service plan defines a set of compute resources for a web app to run. One or more apps can be configured to run on the same computing resources (or in the same App Service plan).
4.	App Service: Create web applications and APIs quickly in the cloud. An HTTP-based service called Azure App Service is used to host mobile back ends, REST APIs, and online apps. You can programme in your preferred language, whether it be Java, Ruby, Node.js,.NET, or.NET Core.
5.	Application Insights: A feature of Azure Monitor, Application Insights offers extensible application performance management (APM) and monitoring for running web applications. Application Insights can be used by developers and DevOps experts to Automatically identify performance issues. Utilize effective analytics technologies to assist in problem diagnosis.
6.	Search Service: Azure's "Azure Search" function is a standout among service offerings. You may incorporate a powerful search service into your apps with this cloud-based search-as-a-service solution. Through a REST API and a. NET SDK, the search service abstracts the difficulties of document retrieval.
7.	Web App Bot: The infrastructure necessary for a bot to access secured resources is provided by the Azure Bot resource. Additionally, it enables the user to speak with the bot through a variety of channels.

•	Google Sites

Lastly, I've used google sites for creating my Database website, in which I have deployed my Azure EduDB-Chatbot. Google Sites is a free website builder byGoogle. You can create websites with collaborators by giving another Google user edit access. Google Sites are compatible with other Google services like Docs, Sheets, and Slides.


## Background working of Azure Cognitive Services:

![architecture-commerce-chatbot](https://user-images.githubusercontent.com/78655015/177655216-0b18b7bf-cbad-48a4-a9c5-975de2b55894.png)

Here, in the above diagram, explains how cognitive services work in background.

With the help of Azure QnA maker we have created an knowledge base, then this knowledge base is connected to our azure chatbot and this chat bot is then embedded to our google site Database Master --> Client Device sends input to the Bot --> Azure Language understanding understands the client queries and automatically chooses an knowledge base and hence finds the similar answer and sends the output.


## Screenshots:

Step 1: Created an Azure Resource Group named "QnABotDBMS”
![image](https://user-images.githubusercontent.com/78655015/178069663-b1fb75a8-c8a8-4eb1-b1fe-6b64a34b178a.png)

Step 2: Created Azure QnA Maker
![image](https://user-images.githubusercontent.com/78655015/178069715-4b8b1f4c-5f75-4d55-abd1-508861128ee9.png)

Step 3: Created an Azure Knowledge Base:
![image](https://user-images.githubusercontent.com/78655015/178069767-6a6d546e-6396-4d1e-8200-75a5f1e52a05.png)
![image](https://user-images.githubusercontent.com/78655015/178069812-b9488882-49a3-444a-93d4-a78fef5ac1b3.png)
![image](https://user-images.githubusercontent.com/78655015/178069831-fc78cf7a-1c12-4580-bcae-03d95cab9ad8.png)
![image](https://user-images.githubusercontent.com/78655015/178069855-cf6a0eeb-81eb-4993-acec-0b9759bf5cb5.png)
![image](https://user-images.githubusercontent.com/78655015/178069876-c792387f-9020-4250-84c7-31803429b064.png)

Step 4: Train the Bot using test feature in Knowledge Base
![image](https://user-images.githubusercontent.com/78655015/178069925-89387bd7-717c-4641-af00-f5712f82bef2.png)

Step 5: Publishing the Bot by creating Azure Bot
![image](https://user-images.githubusercontent.com/78655015/178069965-0abf3d9d-7061-4fcb-8394-a2f1c01bda5f.png)
![image](https://user-images.githubusercontent.com/78655015/178069996-89b1dbbf-2251-4b87-804f-d2f01a20c44c.png)

Step 6: Created a Web App Bot
![image](https://user-images.githubusercontent.com/78655015/178070037-a077f1ef-53b2-483e-8f46-0ec06c9734bd.png)
![image](https://user-images.githubusercontent.com/78655015/178070058-4c432a83-2191-48a7-9993-0e9124fe9c9c.png)

Step 7: Copying the Embedded code and Secret Key to Google Site to enable our chatbot to work
![image](https://user-images.githubusercontent.com/78655015/178070102-0d513641-1c02-479f-9452-82ed11d5ed03.png)

Step 8: Embedded the code in the Google sites and then published the content 
![image](https://user-images.githubusercontent.com/78655015/178070157-048e8e47-4b23-4979-bd9a-e7296dd7c4eb.png)

Step 9: Testing on Google Sites if the bot is working or not
![image](https://user-images.githubusercontent.com/78655015/178070190-a9987a39-1147-4ad1-930f-2d6e4a4bf996.png)
![image](https://user-images.githubusercontent.com/78655015/178070216-44936000-f349-4b87-ae7b-e4f37ee76888.png)
![image](https://user-images.githubusercontent.com/78655015/178070238-48c2630c-8d6c-49c7-9776-ea65988977e5.png)



## Project Link:
https://sites.google.com/view/dbmschatbot/home 


*This repository contains all the information related to the project.*
