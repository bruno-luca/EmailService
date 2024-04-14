# Mail Service

## Project Description

This project is a Java application that implements an email service consisting of a mail server and mail clients. The mail server manages users' email boxes and maintains persistence using files to store messages permanently (not an ideal approach, i know, but those were the requirements for this University project...). The server has a graphical interface to display the log of actions performed by mail clients.

## Mail Server Features

- Manages a list of email boxes.
- Maintains persistence using files to store messages.
- Has a graphical interface to display action and event logs.

## Mail Client Features

- Graphical interface to:
  - Create and send messages to one or more recipients.
  - Read messages from the email box.
  - Reply to or forward messages.
  - Remove messages from the email box.
- Notifies the user when a new message arrives.

## Technical Requirements

- Scalable to many users.
- Developed in Java (JavaFXML) and based on MVC architecture.
- Uses the Observer Observable pattern for communication between controller, views, and model.
- Distributed using Java Socket.
- Handles input errors and server connection issues correctly.
- Parallelizes activities that do not require sequential execution.
- Manages access to resources in mutual exclusion.
- Does not use permanent sockets to connect clients and servers (emulates HTTP but uses socket communication).

## Demonstration

For the demonstration, it is assumed to have 3 email users communicating with each other.

## Usage

1. Clone the repository.
2. Compile and run the server application.
3. Compile and run the client application.

## Contributors

- [Bruno Francesco](https://github.com/FraBrunoPersonal), who developed the Model layer
- [Jean Roland Agbonson Fabrizio](https://github.com/smilefabri), who developed the View layer

