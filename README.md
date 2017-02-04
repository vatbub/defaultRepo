# defaultRepo [![Maven Central](https://img.shields.io/maven-central/v/com.github.vatbub/parentPom.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.github.vatbub%22%20AND%20a%3A%22parentPom%22)
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

##Docs
[Maven Site](http://vatbubmvnsites.s3-website-us-west-2.amazonaws.com/parentPom/0.0.20-SNAPSHOT/site/)

## Contributing
Contributions of any kind are very welcome. Just fork and submit a Pull Request and we will be happy to merge. Just keep in mind that we use [Issue driven development](https://github.com/vatbub/defaultRepo/wiki/Issue-driven-development).
