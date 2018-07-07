# Test Sites

Test target web site(s) for Selenium WebDriver.

## Usage 

The simplest way to use this project is to clone the project locally, build with Maven or importing into an IDE as a Maven project.

### Create a local Clone of the project from github

	git clone https://github.com/Martin-Spamer/test-sites.git

### Build and Install using Maven

Use maven to install the archefacts into your local repository to be used as a dependency.

	mvn install

### Import Project into your IDE

Import the project into your choosen IDE as a Maven project, it can also be run as JUnit test cases, or used as a libray.

	mvn install

### Maven dependency

Add the following dependency to your projects pom.xml file.

	<dependency>
		<groupId>spamer.me.uk</groupId>
		<artifactId>test-sites</artifactId>
		<version>...</version>
	</dependency>
