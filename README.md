# Minecraft Server Installation on Ubuntu 22.04

## Important step!!!
If you don't have a root permission on ur system:
```C++
 sudo -i
```

## Installation
First of step is update ubuntu dependencies:
```C++
 apt update && apt upgrade
```

Third of step is install OpenJDK:
```C++
 apt-get -y install openjdk-16-jdk
```

Third of step is clone repository:
```C++
 git clone https://github.com/Shero1488/MineServer
 cd MineServer
```

If u successfully completed this steps, you can 1st try to start server:
```C++
 ./start.sh
```

When server starting, server create files ( eula.txt, server.properties ), we wiil accept eula:
```C++
 nano eula.txt
```
In this file set 'false' on 'true' and restart server.

If u will edit server port or etc:
```C++
 nano server.properties
```
