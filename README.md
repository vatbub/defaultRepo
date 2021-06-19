# Project deprecation
Tbh, I don't know who used this pom file except for me in my own projects. But in the unlikely event that somebody else uses this pom file: I will deprecate it. In the alsmost 5 years that I am doing Java/Jdk development now, I have learned so much (most importantly that Kotlin is way better than Java) but also, my time is much more limited now than it was back when I started. First of all, I am actually coding now for a living (yay) and I am also doing my PhD. Hence, I decided to deprecate this Pom file for good. If you still need it, feel free to fork the repo or to just copy paste it into your pom file (While still respecting the license, please!). 
I am going to merge `com.github.vatbub:kotlinParentPom` and this pom file in the near future to make them easier to maintain.

Thanks for your attention!

# defaultRepo [![Maven Central](https://img.shields.io/maven-central/v/com.github.vatbub/parentPom.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.github.vatbub%22%20AND%20a%3A%22parentPom%22) [![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=vatbub/defaultRepo)](https://dependabot.com)

The default fok projects repository which also holds the parent pom of all fok projects.

**We are now on Maven Central!!!**
This however lead to a new groupId, sorry.

To use the `com.github.vatbub:parentPom` as your parent, just add the following repositories and parent to your pom:

```xml
...
<parent>
	<groupId>com.github.vatbub</groupId>
	<artifactId>parentPom</artifactId>
	<version>0.0.21</version>
</parent>
...
```

## Build the current snapshot
1. Clone this repository
2. Run `mvn install`

## Build the latest release
Repeat the steps mentioned above but switch to the `release` branch by running `git checkout release` prior to runing `mvn install`.

## Contributing
Contributions of any kind are very welcome. Just fork and submit a Pull Request and we will be happy to merge. Just keep in mind that we use [Issue driven development](https://github.com/vatbub/defaultRepo/wiki/Issue-driven-development).
