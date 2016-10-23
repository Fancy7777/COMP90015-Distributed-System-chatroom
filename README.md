# COMP90015-Distributed-System-chatroom
A chatroom application with good looking GUI and implement all needed functions from specification
 
# data folder includes the keystore and truestore file that can be used in any computer without permission

# image folder includes all the images that needed for GUI

# Further development
May support more failure handling cases.
May improve scalability combine with heartbeat functions. Currently delete the configuration from config.txt. It is not a good feature which definitely needs to be improved. An easiest way to fix it is to just broadcast the messages to all current servers to update their data structure. It still has a few bug that we cannnot solve now.

# Weakeness
1. cannot login as a single server which means cannot have only 1 server configuration in the config.txt
2. donot handle failure handling perfectly. Need not to delete files from config.txt
3. NO MORE?
