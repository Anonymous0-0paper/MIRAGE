# MIRAGE


## Building Apache Flink from Source

Prerequisites for building Flink:

* Unix-like environment (we use Linux, Mac OS X, Cygwin, WSL)
* Git
* Maven (we require version 3.8.6)
* Java 8 or 11 (Java 9 or 10 may work)

```
git clone https://github.com/apache/flink.git
cd flink
./mvnw clean package -DskipTests # this will take up to 10 minutes
```

Flink is now installed in `build-target`.
