# scala-cli-maven-surefire-findbugs-pmd-testng-hello-world

## Description
Analyze source code for potential bugs.
A POC for maven app using testNg
framework with surefire and PMD plugins.

## Tech stack
- scala
- maven
	- findbugs
  - testNg
  - surefire
  - PMD

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- pmd report found at bin/target/site
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
- [PMD example](https://github.com/eugenp/tutorials/blob/master/static-analysis/src/main/resources/logback.xml)
