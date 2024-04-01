# Projet de communication distribuée en Java

Ce projet vise à explorer et comparer trois technologies de communication distribuée en Java : Java RMI, gRPC et les Sockets. Le projet met en œuvre des fonctionnalités spécifiques dans chaque système pour comprendre les différences et les avantages de chacun.

## Installation et exécution

1. Cloner ce dépôt sur votre machine locale.
2. Ouvrir le projet dans votre environnement de développement (IntelliJ IDEA, Eclipse, etc.).
Comment exécuter :
-----------Java RMI :
Accédez au répertoire java-rmi.
Compilez les fichiers Java en exécutant javac *.java.
Lancez le registre RMI en exécutant rmiregistry.
Exécutez le serveur RMI avec java RMIServer.
Exécutez le client RMI avec java RMIClient.
------------Sockets :
Accédez au répertoire sockets.
Compilez les fichiers Java en exécutant javac *.java.
Lancez le serveur de chat avec java ChatServer.
Lancez autant de clients que vous le souhaitez avec java ChatClient.
------------gRPC :
Le module gRPC a été généré à l'aide de Maven. Assurez-vous que le module est correctement généré et compilé.
Lancez le serveur gRPC avec java -jar grpc-messaging-server.jar.
Lancez le client gRPC avec java -jar grpc-messaging-client.jar.

Remarques :
Assurez-vous d'avoir Java installé sur votre machine.
Pour le module gRPC, veuillez réessayer la génération du module à l'aide de Maven.
