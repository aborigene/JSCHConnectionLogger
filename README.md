# JSCHConnectionLogger
Simple program to test JSCH connection and log output to console.

To rum the program simply compile it with maven:

mvn clean build

This will generate a jar file, just run the test like so:

For Java10:
java --class-path "JSchSample-1.0.jar:jsch-0.1.53.jar" com.appdynamics.tests.jschsample.JSchExampleSSHConnection <target_host> <user> <identity_file>

For Java8:
java -classpath "JSchSample-1.0.jar:jsch-0.1.53.jar" com.appdynamics.tests.jschsample.JSchExampleSSHConnection <target_host> <user> <identity_file>

Important that the jsch-0.1.53.jar file must be on the same directory as the sample program is being executed.
