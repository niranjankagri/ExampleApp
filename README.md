# ExampleApp

A minimal Java console application built with the checked-in Gradle 5.2 wrapper and Java 8.

Build and launch: `bash ./gradlew --no-daemon clean build run`.
Run the packaged application: `java -jar build/libs/ExampleApp.jar`.

GitHub Actions checks compilation, packaging and both launch paths on pushes and pull requests. The existing JUnit method is an empty placeholder, so a successful build is not evidence of functional test coverage.
