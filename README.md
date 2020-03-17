Snakeyaml plugin for Jenkins
===

This plugin packages stock Snakeyaml library. 
This component can be used by other plugins as a dependency.
It allows managing library updates independently from plugins.

## How to introduce to your plugin

### Plugins directly depending on snakeyaml

Replace the dependency to `org.yaml:snakeyaml` with the dependency to `snakeyaml`.

* Before:
    ```
    <dependencies>
      ...
      <dependency>
        <groupId>org.yaml</groupId>
        <artifactId>snakeyaml</artifactId>
        <version>1.25</version>
      </dependency>
      ...
    </dependencies>
    ```
* After:
    ```
    <dependencies>
      ...
      <dependency>
        <groupId>io.jenkins.plugins</groupId>
        <artifactId>snakeyaml</artifactId>
        <version>1.25</version>
      </dependency>
      ...
    </dependencies>
    ```

## Release Notes

See the [Changelog](https://github.com/escoem/snakeyaml-plugin/releases).

## License

* Plugin codebase - [MIT License](http://opensource.org/licenses/MIT) 
* Nested library is licensed with [Apache License, Version 2.0](http://www.apache.org/licenses/)

