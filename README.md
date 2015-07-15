# Javolution

The original project is hosted at http://javolution.org/

## Changes
 * `XMLStreamReaderImpl.LocationImpl` is now public and has methods to get the start location of the current tag. By default only the location of the ending of the tag could be retrieved from this `LocationImpl`.

## Builds
Pre-built jars are available at https://github.com/chhh/javolution/releases.<br/>
Built with Oracle's Java 7 compiler.

## Building yourself
You'll need maven installed.<br/>
Change working directory to `<local-repo-path>/java-core` and execute:<br/>
`mvn clean compile package`<br/>
or<br/>
`mvn clean compile package -Dmaven.test.skip=true`<br/>
if some of the non-critical tests fail<br/>

![Powered by Javolution](http://javolution.org/src/site/css/img/javolution.png)
