# Javolution

The original project is hosted at http://javolution.org/

## Changes
 * `XMLStreamReaderImpl.LocationImpl` is now public and has methods to get the start location of the current tag. By default only the location of the ending of the tag could be retrieved from this `LocationImpl`.
 * `XMLStreamReaderImpl#next()` throws more concrete Exceptions when an unexpected
 closing tag or end of xml stream are encountered. Method signature is the same, it
 still `throwns XMLStreamException`, but at least you can check the concrete type with
 `e instanceof XMLUnexpectedEndTagException` instead of checking exception message.

## Builds
Get from [Maven Central](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.github.chhh%22%20AND%20a%3A%22javolution-core-java-msftbx%22). Built with Oracle's Java 7 compiler.  
```xml
<dependency>
    <groupId>com.github.chhh</groupId>
    <artifactId>javolution-core-java-msftbx</artifactId>
    <version>6.11.4</version>
</dependency>
```  


## Building yourself
You'll need maven installed.<br/>
Change working directory to `<local-repo-path>/core-java` and execute:<br/>
`mvn clean compile package`<br/>
or<br/>
`mvn clean compile package -Dmaven.test.skip=true`<br/>
if some of the non-critical tests fail<br/>

![Powered by Javolution](http://javolution.org/css/img/javolution.png)
