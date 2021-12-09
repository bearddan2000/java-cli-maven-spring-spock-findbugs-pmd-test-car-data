# java-cli-maven-spring-spock-findbugs-pmd-test-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app using spock framework.
Uses pmd plugin.

## Tech stack
- java
- groovy
- maven
	- findbugs
  - spring
  - spock
  - pmd

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
- [Code concept](https://www.petrikainulainen.net/programming/testing/writing-unit-tests-with-spock-framework-creating-a-maven-project/)
- [Code build model](https://github.com/christoph-frick/spock-test-logging)
