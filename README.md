# React Firebase Chat 

Creates a chat application using Firebase. Users log in through Google via Firebase Auth and access the chat application where they can see existing chats and type new messages which will be stored in Firebase’s real-time database.

Firebase saves each text message as well as metadata. The messages are parsed and checked for bad words. If any are present, the user is banned for life from logging in, logged out if currently logged in and unable to post further messages. Current bad words within the message are replaced with asterisks. 

See the demo below!

![react-firebase-app](https://www.veed.io/view/f8309f7f-19cc-4ff9-8b30-8200b9c7044c/showcase)
