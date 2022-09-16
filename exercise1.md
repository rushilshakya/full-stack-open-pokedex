# Setting up CI for a Java application

## Language used
Java

## Tools used
The tools used for various steps for CI system in Java include
1. Linting: we can use `Checkstyle` to check for java styles.  `Spotbugs` can be used to statically analyze for bugs
2. Testing: unit testing can be done using `JUnit`.  `TestNG` can be used for integrated testing.  `Selenium` can be used for end to end testing
3. Building: we can use `Gradle` to build our Java applications

## CI Alternatives to Jenkins and GitHub Actions
Looking at the two types of alternatives for CI

a. Self hosted solutions
- TeamCity
- Bamboo CI
- GitLab CI

b. Cloud based solutions
- Buddy
- CodeShip
- Travis CI
- Buildkite
- Shippable

c. Self & Cloud based
- CircleCI

## Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?
With the current information we have that it is going to be released soon, we can assume it is a fairly new application.  It is still early enough in development to standardize so that there aren't too many non-standard components to its CI needs.  
Also since there are only 6 people in the team, we can assume it isn't such a huge codebase.
On account of these assumptions, a cloud-based environment probably will suit our needs.  But further information about special requirements and complexity of the application might change our preference.