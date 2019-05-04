# GraalVM native-image tool compatibility

## Intrduction

  In the scope of the [EU-FOSSSA-2 Project](https://joinup.ec.europa.eu/collection/eu-fossa-2) there a [hackathon](https://eufossahackathon.bemyapp.com/) and [one of the task](EU FOSSA May 2019 Tomcat con](con https://cwiki.apache.org/confluence/display/TOMCAT/EU+FOSSA+May+2019) of the taks is the *GraalVM native-image tool compatibility*

Here the initial descrition:

GraalVM native-image tool compatibility
* Should use https://github.com/apache/tomcat/tree/master/res/tomcat-maven
* Should use the JVM agent to generate reflection information https://github.com/oracle/graal/blob/master/substratevm/CONFIGURE.md
* The agent should be post CR16, to get the commit https://github.com/oracle/graal/commit/8c84d1e5d411d2515a123257c720d85c16edefee

