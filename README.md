# ubuntu_setup_for_java_development
1. install Intellij idea 
- https://www.jetbrains.com/idea/download/#section=linux
- sudo tar -xvf ideaIU-2017.2.tar.gz  -C /opt/
- cd /opt/idea-IU-*/bin
- ./idea.sh
2. install terminator sudo apt-get install terminator
3. install java
- sudo add-apt-repository ppa:webupd8team/java
- sudo apt-get update
- sudo apt-get install oracle-java8-installer
Java will be located at , setup SDK from this folder :/usr/lib/jvm/java-8-oracle
4. sudo apt-get install git

5. sudo apt install mysql-client mysql-server mysql-workbench
6. This is not necessary, i prefer to watch my pc sources
- sudo apt install indicator-multiload
7. Sometimes need to run maven commands from console
- sudo apt install maven
8. Sometimes also need to run bower commands from console
- sudo apt-get install nodejs
- sudo apt-get install npm
- sudo npm install bower -g
