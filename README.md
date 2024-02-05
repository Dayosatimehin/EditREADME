# EditREADME
Project name:  maven project for Behaviour Driven Development(BDD) with Cucumber.

Create a Maven Project:

Use your preferred IDE or command line to create a new Maven project.
Add Cucumber Dependencies to POM.xml:

Open your pom.xml file and add the following dependencies for Cucumber:

Create a Feature File:

Inside the src/test/resources directory, create a new folder named features. Inside this folder, create a feature file (e.g., example.feature) with some Gherkin syntax scenarios.

Create Step Definitions:

Create a package for your step definitions, for example, src/test/java/step_definitions. Inside this package, create a Java class that corresponds to your feature file. Annotate it with @RunWith(Cucumber.class) and specify the location of your feature files and step definitions.

Create Step Definition Methods:

Create a Java class in the step_definitions package to implement the step definitions.

Run Your Tests:

Run the TestRunner class as a JUnit test. Cucumber will execute your feature scenarios using the step definitions you've created.
