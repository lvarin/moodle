# Moodle

This is the OpenShift OKD Helm chart to install Moodle. The images used are from bitnami

## docker compose

In order to install moodle using bitnami's docker compose file:

```bash
$ curl -sSL https://raw.githubusercontent.com/bitnami/bitnami-docker-moodle/master/docker-compose.yml -O
$ docker-compose up -d
```

For more information, like the list of available variables visit:

* https://github.com/bitnami/bitnami-docker-moodle

## Helm

### Quick start

Review and edit the file `k8s/moodle/values.yaml`. Then install the application by:

```bash
helm install release_name k8s/moodle
```
