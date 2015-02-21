# Mavenized OpenOrd layout for gephi

This is a mavenized version of the OpenOrd layout plugin for Gephi. You can use this plugin e.g. if you use the Gephi toolkit in your application and want to manage dependencies with maven.

## Installation

- Checkout the repository
- Run `mvn install`
- Add the dependency to your pom.xml:
  ```xml
<dependency>
    <groupId>org.gephi</groupId>
    <artifactId>openord-layout-plugin</artifactId>
    <version>0.8.2</version>
</dependency>
```

## Credits
The plugin itself was written by [mbastian](https://github.com/mbastian). The original source code can be found at the [Gephi plugin repository](https://github.com/gephi/gephi-plugins) on the openord-layout branch. I added only the pom.xml for Maven.