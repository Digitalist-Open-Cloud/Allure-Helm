# Allure

[Allure](https://docs.qameta.io/allure/) Report is a flexible, lightweight multi-language test reporting tool. It provides clear graphical reports and allows everyone involved in the development process to extract the maximum of information from the everyday testing process.

## Components

This chart installs the following required components:

### Github

- [Allure Docker Service](https://github.com/fescobar/allure-docker-service)
- [Allure Docker Service UI](https://github.com/fescobar/allure-docker-service-ui)

### Dockerhub

- [Allure Docker Service](https://hub.docker.com/r/frankescobar/allure-docker-service/)
- [Allure Docker Service UI](https://hub.docker.com/r/frankescobar/allure-docker-service-ui/)

## Installing the Chart

To install the chart with the release name `my-release`:

```sh
helm install my-release .
```

The command deploys the Allure reporting service and the required components on the Kubernetes cluster in the default configuration.

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```sh
helm delete my-release
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
