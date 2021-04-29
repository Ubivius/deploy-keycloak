# Deploy-Keycloak
A component managing user logins, token generation and user groups for access levels in authentication. 

Work with microservice-authentication as access API.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

## Get Repo Info

```console
helm repo add keycloak <path to chartmuseum or ArtifactHub>
helm repo update
```

_See [helm repo](https://helm.sh/docs/helm/helm_repo/) for command documentation._

## Installing the Chart

To install the chart directly from the Github repo with the release name `keycloak`:

```console
helm install keycloak chart/ --values chart/values.yaml
```

To install the chart from ArtifactHub with the release name `keycloak`:

```console
helm install keycloak <org name>/keycloak --version <version> 
```

## Uninstalling the Chart

To uninstall/delete the keycloak deployment:

```console
helm delete keycloak
```
For more information visit https://www.keycloak.org.
