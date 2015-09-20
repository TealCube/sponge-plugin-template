# Template for Sponge Plugins

A template made for simple Sponge plugins. Uses Gradle.

## Usage
- Download/fork this repository.
- Make changes to build.gradle and settings.gradle as necessary
- Modify project files as necessary
  - Make sure to change the package and class name of the `@Plugin` annotated class

## Build

### CLI
- Open CLI of your choice in root project directory
- Run `gradlew.bat` if on Windows, `./gradlew` if on *nix systems
- ???
- Profit!
  - Your plugin's files will be located in the `build/libs` directory.

### IntelliJ IDEA
- Open CLI of your choice in root project directory
- Run `gradlew.bat idea` if on Windows, `./gradlew idea` if on *nix systems
- ???
- Profit!
  - Open IntelliJ and point it at the root project directory

### Eclipse
- Open CLI of your choice in root project directory
- Run `gradlew.bat eclipse` if on Windows, `./gradlew eclipse` if on *nix systems
- ???
- Profit!
  - Open Eclipse and point it at the root project directory
