# Big-Data

```
apt install openssh-server


sudo apt update
sudo apt install wget
mkdir /usr/java

sudo apt update && sudo apt upgrade
apt-cache search openjdk-8 | grep openjdk-8
apt-cache search openjdk-8 | grep openjdk-8-jdk -y
apt install openjdk-8-jdk -y
java --version
java version
java
which java
sudo update-alternatives --config java
echo $JAVA_HOME
#https://www.linuxcapable.com/how-to-install-openjdk-8-on-ubuntu-linux/
echo 'export JAVA_HOME=usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java' >> ~/.bashrc
echo $JAVA_HOME
source ~/.bashrc 
echo $JAVA_HOME
man source

echo 'export HADOOP_HOME=u/home/dilip/hadoop-3.3.6/' >> ~/.bashrc

-------------------------------------------------
echo 'export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java' >> ~/.bashrc
source ~/.bashrc 
echo $JAVA_HOME
vim hadoop-env.sh 
echo 'export HADOOP_HOME=/home/dilip/hadoop-3.3.6/' >> ~/.bashrc
source ~/.bashrc 
echo $HADOOP_HOME

echo $PATH
vim ~/.bashrc 
source ~/.bashrc 
echo $PATH
vim hadoop-env.sh 
./bin/hadoop
ls /usr/lib/jvm/java-8-openjdk-amd64/jre/bin/java
echo $JAVA_HOME
vim /home/dilip/hadoop-3.3.6/etc/hadoop/hadoop-env.sh
vim ~/.bashrc 
source ~/.bashrc 
./hadoop
echo $JAVA_HOME
vim /home/dilip/hadoop-3.3.6/etc/hadoop/hadoop-env.sh
./hadoop
source /home/dilip/hadoop-3.3.6/etc/hadoop/hadoop-env.sh
./hadoop
vim /home/dilip/hadoop-3.3.6/etc/hadoop/hadoop-env.sh
./hadoop
cat $HADOOP_HOME
echo $HADOOP_HOME
vim /home/dilip/hadoop-3.3.6/etc/hadoop/hadoop-env.sh
./hadoop
vim /home/dilip/hadoop-3.3.6/etc/hadoop/hadoop-env.sh
./hadoop
hadoop fs

hdfs dfs

hadoop fs -ls

hadoop fs -ls -l
hadoop fs -ls 
cd ..
hadoop fs -copyFromLocal ~/Downloads/wordcount.txt /test/
pwd
mkdir test
hadoop fs -copyFromLocal ~/Downloads/wordcount.txt test
ls
hadoop fs -ls 
hadoop fs -ls test
```
