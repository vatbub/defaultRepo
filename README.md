# defaultRepo
The default fok projects repository which also holds the parent pom of all fok projects.

To use the `fokprojects.parentPom` as your parent, just add the following repositories and parent to your pom:

```xml
...
<repositories>
  ...
    <repository>
      <id>fokReleaseRepo</id>
      <name>FOK Release Repository</name>
      <url>http://vatbub.bplaced.net/mavenRepo/release/</url>
    </repository>
    <repository>
      <id>fokSnapshotRepo</id>
      <name>FOK Snapshot Repository</name>
      <url>http://vatbub.bplaced.net/mavenRepo/snapshots/</url>
    </repository>
  ...
  </repositories>
  ...
  <parent>
		<groupId>fokprojects</groupId>
		<artifactId>parentPom</artifactId>
		<version>0.0.2</version>
	</parent>
	...
```
