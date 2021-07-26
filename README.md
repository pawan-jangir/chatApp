

## Usage Guide -

1. Install nodejs & mongodb on system. Check using the following commands in the terminal -

2. Open your terminal and run the following -

$ npm install
$ node server.js

3. after this open the link http://localhost:3002/chat.html to access the chat interface

4. Type your name and the 2nd person name and press done to establish a connection. You will see the entire chat history retrieved between the two people.

5. Open the same URL in another browser/tab and establish the other half of the connection

6. Send messages from any end to see the functioning

7. Close when you have to exit the chat 

## Functionality -
- When a user logs in, his'her record is maintained in online users collection, and the entire chat history is retrived from the database and displayed using socket.io
- When he sends messages, it's checked if the recipient is online or not. If yes, message is sent to him. If not, nothing happens. In both the cases, message is stored in database for later access
- When a user disconnects, he'she is  removed from online users database


Note: I have created very simple example just to show the chat functionality, we can do much more with this like group chat in that we can use broadcast method to send message to multiple users.
there can be some bug also.


