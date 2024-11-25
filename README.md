# Essentials
This is an exercise from Introducing Maven on how to create a multimodule project.

## Commands

Parent Project:
mvn archetype:generate -DgroupId=com.apress.gswmbook
-DartifactId=gswm-parent -Dversion=1.0.0-SNAPSHOT
-DarchetypeGroupId=org.codehaus.mojo.archetypes
-DarchetypeArtifactId=pom-root

Web Project:
mvn archetype:generate -DgroupId=com.apress.gswmbook
-DartifactId=gswm-web -Dversion=1.0.0-SNAPSHOT -Dpackage=war
-DarchetypeArtifactId=maven-archetype-webapp

Service Project:
mvn archetype:generate -DgroupId=com.apress.gswmbook
-DartifactId=gswm-service -Dversion=1.0.0-SNAPSHOT
-DarchetypeArtifactId=maven-archetype-quickstart
-DinteractiveMode=false

Repository Project:
mvn archetype:generate -DgroupId=com.apress.gswmbook
-DartifactId=gswm-repository -Dversion=1.0.0-SNAPSHOT
-DarchetypeArtifactId=maven-archetype-quickstart
-DinteractiveMode=false

## Updates to POM

Updated source encoding and compiler release on child module POMs.

## Git Ignore

Combined Java, Maven, and VS Code .gitignore files from GitHub.

## References

https://github.com/github/gitignore
