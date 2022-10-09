# hadoop-on-ubuntu-based-on-Parallels-Desktop
1. install Linux
2. install JAVA JDK 8
~~~
sudo apt-get update
sudo apt install openjdk-8-jdk
~~~
3. insert $JAVA_HOME into enveronment
~~~
sudo vi /etc/environment
~~~
~~~
JAVA_HOME="/usr/lib/jvm/java-8-openjdk-arm64/jre/bin/java"
~~~
4. reload env
~~~
source /etc/environment
~~~
5. check up
~~~
echo $JAVA_HOME
~~~
