# Amazon Lex Chat Bot
Simple Amazon Lex Chat Bot that replicates a banking app interface

First I created a new Lex bot from scratch, configured basic Greeting messages and Fallback fullfillment messages. Next I developed a custom slot in Amazon Lex to handle different bank account types - Checking, Savings, and Credit. Next I created a new intent called CheckBalance that asks for the user's bank account type and also asks for verficiation of user's date of birth. At this point it was giving the output message Fullfillment successful instead of the total balance. So then I integrated AWS Lambda and wrote a simple python script to generate a random number and configured it's alias with the chatbot so that the output is a number in USD instead of Fullfillment successful. 


![12](https://github.com/user-attachments/assets/3a34b9a1-cb6a-4764-8144-35e23cd38733)
