# constrast_security_demo
JenkinsPipeline example using the Java PetClinic Application
This is a Jenkins pipeline that:

Downloads and builds a vulnerable version of Petclinic
Runs a very basic functional test
Uses Contrast Security as a quality gate against the result
Prerequisites:

Jenkins - tested with version 2.180
A Contrast Security account
Version 2.6 of the Contrast Security Jenkins Plugin - see https://github.com/jenkinsci/contrast-continuous-application-security-plugin
