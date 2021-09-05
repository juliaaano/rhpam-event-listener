# RHPAM Event Listener
[![ci](https://github.com/juliaaano/rhpam-event-listener/actions/workflows/ci-cd.yml/badge.svg)](https://github.com/juliaaano/rhpam-event-listener/actions/workflows/ci-cd.yml)

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
