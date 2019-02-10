# project-b

Example project that depends on [project-c](../project-c).

The dependency on project-c is declared in the [settings.gradle](settings.gradle) file using the `includeBuild` directive.

## Building the Project
Run the following command to build the project:

    ./gradlew build