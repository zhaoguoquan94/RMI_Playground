# Java RMI sample code
## RUN
 `javac -d ./ Hello.java Server.java Client.java`

 `rmiregistry &`

 `java -classpath ./ -Djava.rmi.server.codebase=file:classDir/ Server &`

 `java  -classpath ./ Client`