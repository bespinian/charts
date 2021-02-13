# Helm chart repo

You can add this repo to Helm with the following command

```
helm repo add bespinian https://bespinian.github.io/charts
```

You can then search the repo with the following command:

```
helm search repo bespinian
```

After adding new charts to the repo, run the following command to update `index.yaml`:

```
helm repo index .
```

Then, commit and push your changes to publish them.
