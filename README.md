# Chat Server Project
This is a chat server written with HTML, CSS, and Javascript that utilizes NodeJS and Socket.io to run on a local host. In this chat server, users can register with a username, and then create and join chat rooms to send and receive messages. User's messages show their username to everyone in the room, and users can send private messages to another user in the same room. Chat room creators can temporarily kick and permanently ban users from their created chat room(s), and can also send an alert all users in the chat. Chat room creators can grant these privileges (kicking, banning, alerting, privilege granting,) to other users as well. All information is stored temporarily and not in a database, so reloading the page destroys all chat rooms and user info.

To run this project:
Have NodeJS and Socket.io installed. NodeJS modules must be in a parallel directory to client.html. Run "node" in the terminal to activate the server, and then run client.html.
