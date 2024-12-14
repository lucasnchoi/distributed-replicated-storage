# Distributed & Replicated Storage Service
How to Run: Use Apache Ant to build the ecs, server and client.
To start run ecs with the necessary values e.g. java -jar ecs.jar -a <address> -p <port>
Then run as many server instances as you would e.g. java -jar server.jar -a <address> -p <port> -b <ecsAddress:ecsPort> -d <(optional) set directory for this servers data> -c <(optional) cache size>
Finally run the client and connect it to any server, use the help command to find all the available commands, including connect/disconnect to servers, and put and get for inserting, accessing and deleting KV pairs.
