# TCP based Texting Application
## Overview
The TCP Texting Application is a Java-based LAN chat application that allows users to communicate via group and private chats over a local network. The application provides a user-friendly graphical interface for initiating and managing chat sessions.

## Features
* Group Chat: Allows multiple users to join a common chat room and communicate with each other.
* Private Chat: Facilitates one-on-one conversations between users.
* IP Address Retrieval: Automatically retrieves the user's IP address for easy connection setup.
* Network Ping: Checks network connectivity and latency.

## Getting Started
### Prerequisites
* Java Development Kit (JDK) installed
* NetBeans IDE (optional but recommended for ease of use)

### Running the Application
1. Clone the Repository:
`git clone https://github.com/yourusername/tcp-texting-application.git`
`cd tcp-texting-application`

2. Build the Project:
If you're using NetBeans, simply open the project and build it. Alternatively, you can use the provided Ant build script:
`ant build`

3. Run the Application:
Execute the JAR file:
`java -jar dist/LanChatApplication.jar`

## Usage
* **Group Chat**: Start the application, select "Group Chat" from the main menu, and follow the prompts to join or create a chat room.
* **Private Chat**: Select "Private Chat" and follow the prompts to initiate a one-on-one conversation.
* **IP Address and Network Ping**: Use the relevant options from the main menu to retrieve your IP address or check network connectivity.
