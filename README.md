# RHDM Event Listener
[![Build Status](https://travis-ci.com/juliaaano/rhdm-event-listener.svg)](https://travis-ci.com/juliaaano/rhdm-event-listener)

Suitable for KIE Server deployments.

## Maven
```
mvn clean install
```

## Maven deploy
```
mvn deploy --activate-profiles deploy
```
Without distribution management:
```
mvn deploy -DaltDeploymentRepository='nexus::default::http://user:password@maven-repo-host/repo-path/'
```
