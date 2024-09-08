## Assignment - Chat application with Socket.IO

Socket.IO chat application made from modifying this [repository.](https://github.com/RaoofJM/nodejs-socketio-chat-application) Small changes were made which are shown on the screenshots.

## Application

When you open the localhost you first have to choose your nickname

<img src="screenshots/nickname_ss.png" alt="nickname" width="500"/>

Screenshot of room 1

<img src="screenshots/room1_ss.png" alt="room1" width="500"/>

Screenshot of room 2

<img src="screenshots/room2_ss.png" alt="room2" width="500"/>

Screenshot of room 3

<img src="screenshots/room3_ss.png" alt="room3" width="500"/>

## Explain namespaces in Socket.IO? How they are different from rooms and how could you use those in your app?

Namespaces in Socket.Io is a way to divide seperate channel connections by using specific name for a socket connection. For example /chat , /admin & /notifications . You could use it to handle different functions of your application. 