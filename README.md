# ubuntu-java-newrelic
A Ubuntu Linux docker image based on `openjdk:8-jdk` with the
[New Relic](https://newrelic.com/) Java agent installed into `/opt/newrelic`.


## Usage

Mount (or copy) the `newrelic.yml` configuration file into `/opt/newrelic`. At
a minimum the `license_key` and `app_name` settings must be updated.

Add `-javaagent:/opt/newrelic/newrelic.jar` as a JVM Option.


## Docker Hub

Available on Docker Hub as [rigoford/ubuntu-java-newrelic](https://hub.docker.com/r/rigoford/ubuntu-java-newrelic).


## Further details

Refer to https://docs.newrelic.com/docs/agents/java-agent for further details.
