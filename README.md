# JUnit 5 Examples

[![Build Status](https://travis-ci.org/ddubson/junit5-kotlin-examples.svg)](https://travis-ci.org/ddubson/junit5-kotlin-examples)

## Running all tests cases

### via Gradle

Run the following in the console:

```
./gradlew test
```

`test` command runs the JUnit 5 Gradle Plugin `:junitPlatformTest` task
which executes the test suite found in `src/test/kotlin` directory.

`junitPlatformTest` task depends on having an engine on the classpath.
For our example suite, we are using the Jupiter engine.