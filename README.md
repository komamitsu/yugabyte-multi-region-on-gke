# yugabyte-multi-region-on-gke
One click setup scripts for deploying YugabyteDB multi-region cluster on GKE.

The purpose of this project is to simplify the setup of YugabyteDB multi-region cluster on GKE following the guideline at https://docs.yugabyte.com/preview/deploy/kubernetes/multi-cluster/gke/helm-chart/. This project isn't intended for production environment setup.

## Prerequirements

Ensure that you have prepared your GCP project.

Additionally, make sure the following tools are installed:

- Kubectl
- Gcloud CLI
- Python

## Configuration

Modify the `config` file according to your requirements.

## Run

Execute the following command:

```
$ ./all
```
