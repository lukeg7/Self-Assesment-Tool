# Self Assesment Tool for CSC240

### Setting up
1.) Installed JDK via Oracle website<br/> 
2.) Installed Homebrew via macOS terminal<br/> 
3.) Installed Maven via macOS terminal<br/>  

### Project Creation 
1.) Run the Maven Project Generation Command<br/>
```bash
mvn archetype:generate -DgroupId=com.example -DartifactId=self-assessment-tool -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false
```
2.) Open the pom.xml file and Add Apache POI Dependecy:
```xml
<dependencies>
    <dependency>
        <groupId>org.apache.poi</groupId>
        <artifactId>poi-ooxml</artifactId>
        <version>5.2.3</version>
    </dependency>
</dependencies>
```
3.) Run Build Command in project directory via macOS terminal: 
```bash
cd ~/your-project
mvn clean install
```
