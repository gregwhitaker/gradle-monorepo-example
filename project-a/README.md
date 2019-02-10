# project-a

Example project that depends on [project-b](../project-b).

The dependency on project-b is declared in the [settings.gradle](settings.gradle) file using the `includeBuild` directive.

## Building the Project
Run the following command to build the project:

    ./gradlew build
    
## Running the Project
Run the following command to start the application:

    ./gradlew run
    
If successful, you will see the following in the console:

    > Task :run
    FooBar