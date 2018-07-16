# Chat-Server
Server which is deployed on heroku to be used by the [chat-app](https://github.com/supunvimukthi/ChatApp). 
- *deployed on heroku - [link](https://evening-ridge-37409.herokuapp.com/)* 
 
### Four routes to access the mongo db used for the chat-app. 
- **GET-to get the list of contacts - */users/list*** 
- **POST-to check for user login crdentials with the database - */users/login*** 
- **POST-to save the sent message in the database - */messages/send*** 
- **POST-to get all the messages between two users to be displayed in the chat screen - */messages/receive*** 
