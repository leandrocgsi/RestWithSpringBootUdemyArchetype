# Rest with Spring Boot Udemy Archetype

## Step 1 - GIT Clone

```
git clone https://github.com/leandrocgsi/RestWithSpringBootUdemyArchetype.git
```
## Step 2 - Access folder and run command

```
mvn clean install
```

## Step 3 - Run Maven Archetype

```
mvn archetype:generate
    -DarchetypeGroupId=br.com.erudio
    -DarchetypeArtifactId=rest-with-springboot-udemy-archetype
    -DarchetypeVersion=0.0.1-SNAPSHOT (YOUR_VERSION)
    -DgroupId=br.com.semeru (YOUR_GROUP_ID)
    -DartifactId=rest-api-from-archetype (YOUR_ARTIFACT_ID)
```
