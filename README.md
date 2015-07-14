# Javolution

The original project is hosted at http://javolution.org/

## Changes
 * `XMLStreamReaderImpl.LocationImpl` is now public and has methods to get the start location of the current tag. By default only the location of the ending of the tag could be retrieved from this `LocationImpl`.

## To build java jars yourself
You'll need maven installed.
Change working directory to `<local-repo-path>/java-core` and execute:<br/>
`mvn clean compile package`

![Powered by Javolution](http://javolution.org/src/site/css/img/javolution.png)
