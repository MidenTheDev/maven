# Miden’s Maven Repository:

This repository hosts the maven repository of all of my plugins.



# Maven:

To add the repo to your project using maven, add the following to your pom.xml:

```xml
<repository>
    <id>midens-repo</id>
    <url>https://midenthedev.github.io/maven/</url>
</repository>
```

# Gradle:

To add the repo to your project using gradle, add the following to your settings.gradle file:

```gradle
dependencyResolutionManagement {
	repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
	repositories {

	}
}
```
