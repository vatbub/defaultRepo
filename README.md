# defaultRepo
The default fok projects repository which also holds the parent pom of all fok projects.

To use the `fokprojects.parentPom` as your parent, just add the following repositories and parent to your pom:

```xml
...
<repositories>
	...
		<repository>
			<snapshots>
				<enabled>false</enabled>
			</snapshots>
			<id>bintray-vatbub-fokprojectsSnapshots</id>
			<name>bintray</name>
			<url>http://dl.bintray.com/vatbub/fokprojectsSnapshots</url>
		</repository>
		<repository>
			<snapshots />
			<id>snapshots</id>
			<name>libs-snapshot</name>
			<url>https://oss.jfrog.org/artifactory/libs-snapshot</url>
		</repository>
	</repositories>
  	...
  <parent>
		<groupId>fokprojects</groupId>
		<artifactId>parentPom</artifactId>
		<version>0.0.2</version>
	</parent>
	...
```
