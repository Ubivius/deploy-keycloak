# Keycloak Helm Chart

- keycloak · bitnami/keycloak (https://artifacthub.io/packages/helm/bitnami/keycloak)

## Get Repo Info

```console
$ helm repo add bitnami https://charts.bitnami.com/bitnami
$ helm repo update
```

## Installing the Chart

To install the chart with the release name `keycloak`:

```console
$ helm install keycloak --version <version> bitnami/keycloak -f values.yaml
```

## Uninstalling the Chart

To uninstall/delete the `keycloak` deployment:

```console
$ helm delete keycloak
```

The command removes all the Kubernetes components associated with the chart and deletes the release.
