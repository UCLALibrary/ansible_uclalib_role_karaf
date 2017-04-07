# UCLALib Ansible Role: Apache Karaf

Deploys Apache Karaf on RHEL servers

Apache Karaf is an application container (OSGi) environment.

Documentation for Karaf is available [here](http://karaf.apache.org/manual/latest/).

## Dependencies

* uclalib_role_java

## Variables

The following are variables defined as defaults - change these in the play file to customize:

karaf_version - defines the version of Apache Karaf to use (e.g. 4.0.5)

karaf_url - define the URL to obtain the Karaf archive file

java_home - define the path to the JAVA_HOME directory

java_xms - define the JVM memory minimum value (in MB)

java_xmx - define the JVM memory maximum value (in MB)

karaf_home -  define the Karaf home directory (this is where Karaf )

karaf_user - define the user that will run the Apaceh Karaf service
