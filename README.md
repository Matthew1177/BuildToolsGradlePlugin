# BuildTools Gradle Plugin
BuildTools Gradle Plugin is an open source Gradle script plugin that interfaces [Spigot's BuildTools](https://www.spigotmc.org/wiki/buildtools/) with Gradle.
## Use in your project
Add the following to your `build.gradle`.
```groovy
apply from: 'https://raw.githubusercontent.com/Matthew1177/BuildToolsGradlePlugin/main/buildtools.gradle'
```
## Usage
This plugin supports building of any [version](https://hub.spigotmc.org/versions/) of Spigot.
```groovy
dependencies {
    // Adds SpigotAPI 1.16.5 as a dependency
    compileOnly spigotApi('1.16.5')
    // Adds Spigot 1.16.5 as a dependency
    compileOnly spigot('1.16.5')
}
```
