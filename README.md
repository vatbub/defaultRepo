# defaultRepo
The default fok projects repository which also holds the parent pom of all fok projects.

**We are now on Maven Central!!!**
This however lead to a new groupId, sorry.

To use the `com.github.vatbub:parentPom` as your parent, just add the following repositories and parent to your pom:

```xml
...
<parent>
	<groupId>com.github.vatbub</groupId>
	<artifactId>parentPom</artifactId>
	<version>0.0.17</version>
</parent>
...
```

## Build the current snapshot
1. Clone this repository
2. Run `mvn install`

## Build the latest release
Repeat the steps mentioned above but switch to the `release` branch by running `git checkout release` prior to runing `mvn install`.
