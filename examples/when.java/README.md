# chunked

This sample shows running jersey inside vert.x using when.java promises and `WhenJerseyServer`

## Run It

1. Run from the command line `java -jar target/vertx-jersey-examples-when.java-Version-fat.jar -conf src/test/resources/config.json'
2. Run from inside IDEA creating a JAR Application build configuration with program arguments `-conf src/test/resources/config.json`


Try the following url in your browser:
* `http://localhost:8080/when`


## The Configuration

The vertx-when jar is used to deploy a `JerseyServer`.  See the config.json file for binders and jersey configuration.
