## Dependencies

Tyrus is built, assembled and installed using Maven. Tyrus is
deployed to the Maven Central repository at the following location:
<http://repo1.maven.org/>. Jars, Jar sources, Jar JavaDoc and samples
are all available on the Maven Central repository.

An application depending on Tyrus requires that it in turn includes
the set of jars that Tyrus depends on. Tyrus has a pluggable
component architecture so the set of jars required to be include in the
class path can be different for each application.

All Tyrus components are built using Java SE 7 compiler. It means, you
will also need at least Java SE 7 to be able to compile and run your
application.

Developers using maven are likely to find it easier to include and
manage dependencies of their applications than developers using ant or
other build technologies. This document will explain to both maven and
non-maven developers how to depend on Tyrus for their application. Ant
developers are likely to find the Ant Tasks for Maven very useful.

In general, if you're not using Maven, most probably you'd need to
download dependencies (jar files) directly from the Maven repository.

### Running on Glassfish

All you need for your project if you are using Glassfish 4.0 is to declare
provided dependency on websocket-api.

```xml
<dependency>
    <groupId>javax.websocket</groupId>
    <artifactId>javax.websocket-api</artifactId>
    <scope>provided</scope>
    <version>1.0</version>
</dependency>
```

Glassfish 4.1 includes WebSocket API 1.1:

```xml
<dependency>
    <groupId>javax.websocket</groupId>
    <artifactId>javax.websocket-api</artifactId>
    <scope>provided</scope>
    <version>1.1</version>
</dependency>
```


### Running on Servlet 3.1 compatible container

Assumption here is that Tyrus or WebSocket runtime is not already included, so you need to
package it with your application (dependencies are not provided).

```xml
<dependency>
    <groupId>org.glassfish.tyrus</groupId>
    <artifactId>tyrus-container-servlet</artifactId>
    <version>1.12</version>
</dependency>

<dependency>
    <groupId>org.glassfish.tyrus</groupId>
    <artifactId>tyrus-client</artifactId>
    <version>1.12</version>
</dependency>
```

### Standalone client

WebSocket client based on Grizzly (supports Java SE 6)

```xml
<dependency>
    <groupId>org.glassfish.tyrus.bundles</groupId>
    <artifactId>tyrus-standalone-client</artifactId>
    <version>1.12</version>
</dependency>
```

WebSocket client based on Java SE 7 Asynchronous IO

```xml
<dependency>
    <groupId>org.glassfish.tyrus.bundles</groupId>
    <artifactId>tyrus-standalone-client-jdk</artifactId>
    <version>1.12</version>
</dependency>
```

### Bundle for non-maven users

There is a bundle which contains all files needed successful deployment and run of any JSR-356 (WebSocket API for Java)
based application

[WebSocket RI archive](http://search.maven.org/remotecontent?filepath=org/glassfish/tyrus/bundles/websocket-ri-archive/1.12/websocket-ri-archive-1.12.zip)

If you need just client implementation, you should use Tyrus Standalone Client bundle

[Tyrus Standalone Client](http://search.maven.org/#artifactdetails%7Corg.glassfish.tyrus.bundles%7Ctyrus-standalone-client%7C1.12%7Cjar)
