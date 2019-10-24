# How to create a new project using this archetype
- Clone this project
- Run "mvn clean install -DskipTests"
- Run "mvn archetype:generate -DarchetypeGroupId=com.traceable.archetype -DarchetypeArtifactId=traceable-automation-archetype -DarchetypeVersion=1.0-SNAPSHOT -DgroupId=<Your New Project Group ID> -DartifactId=<You New Project Artifact ID>  -Dversion=1.0-SNAPSHOT"
