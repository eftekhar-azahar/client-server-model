# Client-Server Chat Room using Python Socket 

  

## Table of Contents 

  

- [Introduction](#introduction) 

- [Features](#features) 

- [Prerequisites](#prerequisites) 

- [Usage](#usage) 

  - [Server](#server) 

  - [Client](#client) 

- [Example](#example) 

- [Contributing](#contributing) 

- [License](#license) 

  

## Introduction 

  

This Python-based chat room system utilizes a client-server model to enable real-time text communication. The chat room comprises a server that accepts connections from multiple clients, allowing them to exchange messages. It's a simple, easy-to-understand implementation of socket programming in Python. 

  

## Features 

  

- Multiple clients can connect to the server simultaneously. 

- Real-time, two-way text communication. 

- The server can broadcast messages to all connected clients. 

- Support for custom usernames. 

- Graceful handling of client disconnects. 

  

## Prerequisites 

  

Before using this chat room application, ensure you have the following: 

  

- Python 3.x installed on your machine. 

- Basic knowledge of how to run Python scripts.
- Insatll pakage socket

- Terminal or command prompt to execute the server and client scripts. 

  

## Usage 

  

### Server 

  

1. Open a terminal or command prompt. 

2. Navigate to the project directory. 

3. Run the server script using the following command: 

  

   ```bash 

   python server.py 

   ``` 

  

4. The server will start and listen for incoming client connections on a specified port (default: 12345). 

  

### Client 

  

1. Open a new terminal or command prompt for each client you wish to connect. 

2. Navigate to the project directory. 

3. Run the client script using the following command: 

  

   ```bash 

   python client.py 

   ``` 

  
