# hadoop-3.0.0

## Prerequisite

**Java**

Download the Java 1.8 from https://java.com/en/download/
Once installed confirm that you’re running the correct version from command line using ‘java -version’ command, output of which you can confirm in command line like this

- Java

```
C:\WINDOWS\system32>java -version
java version "1.8.0_111"
Java(TM) SE Runtime Envinronment (build 1.8.0_111)
Java HotSpot(TM) 64-Bit Server VM (build 25.111-b14, mixed mode)
```

- OpenJDK

```
C:\WINDOWS\system32>java -version
openjdk version "11.0.8" 2020-07-14
OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
```

The next step was to install a Hadoop distribution. To do so, I’ve decided to download the most recent release Hadoop 3.0.0-alpha2 (25 Jan, 2017) in a binary form, from the Apache Download Mirror at http://hadoop.apache.org/releases.html
Once the hadoop-3.0.0-alpha2.tar.gz (250 MB) downloaded, I’ve extracted it by using WinRAR (installed in the previous step) into C:\hadoop-3.0.0-alpha2 folder
