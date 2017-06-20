# Hadoop_Exmp
reference Hadoop

#JAVA

$ cd /usr/local/lib
$ tar xvfz jdk-8u79-linux-x64.gz
$ ln -s jdk1.8.0_131 java
$ vi /etc/profile
  export JAVA_HOME=/usr/local/lib/java
  export PATH=$PATH:$JAVA_HOME/bin
  export CLASS_PATH="."
 
$ source /etc/profile
