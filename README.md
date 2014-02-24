IntelliJ Open API Maven Repository
========

This (unofficial) repository contains the IntelliJ Open API jars requires to build the Infinitest plugin for Idea with Maven.

To use these in one of your plugins add this to your pom.xml:

```
<repositories>
	<repository>
		<id>infinitest-openapi</id>
		<name>3rd party IntelliJ Open API repository for Infinitest</name>
		<url>https://github.com/szpak/maven-intellij-openapi/raw/infinitest/</url>
	</repository>
</repositories>

<dependencies>
	<dependency>
		<groupId>org.infinitest.intellij</groupId>
		<artifactId>intellij-openapi</artifactId>
		<version>12.1.4</version>
		<scope>provided</scope>
	</dependency>
	<dependency>
		<groupId>org.infinitest.intellij</groupId>
		<artifactId>intellij-util</artifactId>
		<version>12.1.4</version>
		<scope>provided</scope>
	</dependency>
	<dependency>
		<groupId>org.infinitest.intellij</groupId>
		<artifactId>intellij-annotations</artifactId>
		<version>12.1.4</version>
		<scope>provided</scope>
	</dependency>
	<dependency>
		<groupId>org.infinitest.intellij</groupId>
		<artifactId>intellij-extensions</artifactId>
		<version>12.1.4</version>
		<scope>provided</scope>
	</dependency>
	<dependency>
		<groupId>org.infinitest.intellij</groupId>
		<artifactId>intellij-idea</artifactId>
		<version>12.1.4</version>
		<scope>provided</scope>
	</dependency>
	<dependency>
		<groupId>org.infinitest.intellij</groupId>
		<artifactId>intellij-trove4j</artifactId>
		<version>12.1.4</version>
		<scope>provided</scope>
	</dependency>
</dependencies>
```

The files hosted here have been taken from the Intellij Community distribution, you can find out more at http://www.jetbrains.org/display/IJOS/Home

This repository is a fork of [Vektah's repository](https://github.com/Vektah/maven-intellij-openapi/) customized for [Infinitest](https://github.com/infinitest/infinitest). Thanks Vektah for the idea!

