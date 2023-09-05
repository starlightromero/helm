# Helm Charts

Helm repo in GitHub without GitHub pages.


# Adding a new version or chart to this repo

```bash
$ helm package $YOUR_CHART_PATH/ # build the tgz file and copy it here
$ helm repo index . # create or update the index.yaml for repo
```

# How to use the repo

```bash
$ helm repo add sample 'https://raw.githubusercontent.com/starlightromero/gatekeeper-library/main/'
$ helm repo update
```
