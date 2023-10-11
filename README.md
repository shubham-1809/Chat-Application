# Chat-Application
This is a real time chat web application allowing multiple users can to engage in instant messaging. <br><br>
1. Front end user interface is built using HTML, CSS and JavaScript that will ask user to enter his/her name and after that allows them to enter the chat room. <br><br>
2. A chat user interface is just like a whatsapp user interface where message sent by a user will appear on the right side and message recieved by a user will appear on the left side. <br><br>
3. Backend server is built using Node.js and Socket.io which is connected to the front end using one of the Socket.io library. Whenever a user connects to the server or sends a message the Socket.io will listen to that event and then it broadcast this event to all the users connected to this server. <br><br>
4. Similary JavaScript running on the users end will listen to any of the events pushed by the server and will render those events on the frontend. <br><br>
5. A user tracking functionality is also implemented which tracks whenever a users join and leave the chat room. This functionality will let other users know that whether any particular user has joined or left the chat room. <br><br>
6. Tech Stack(frontend): HTML | CSS | JavaScript <br>
   Tech Stack(backend): Node.js | Socket.io
