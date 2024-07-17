# Helm Charts

This repository will be used to store my personal helm charts created for testing and production use.
If this feeds your needs use it as it is or contribute.

## Usage

Just add this as a new repository for your local helm installation:

```
root@sofx1022k3s3018:~# helm repo add kpucko-charts https://kpucko.github.io/Helm_Charts
"kpucko-charts" has been added to your repositories
root@sofx1022k3s3018:~# helm repo update
```

## Automation
Every change in the repository will be done through PR. After the merge to main branch, the CI/CD automation will be triggered which will refresh the index of the charts.
