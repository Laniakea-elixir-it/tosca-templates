# TOSCA templates

TOSCA template for Laniakea

## Galaxy

| Template | Description | Continuous testing |
| -------- | ----------- | ------------------ |
| `galaxy.yml` | Perform the deployment of a Galaxy starting from a clean Virtual Machine (Live Build). Only the Galaxy production environment is installed. | yes |
| `laniakea-galaxy-express.yml` | Perform the deployment of a Galaxy starting from a cloud image with Galaxy and all its companion software already installed (Express Build). The template integrate also the possibilty to encrypt the persistent volume, save user credentials on Vault, and the installation of Laniakea Utils API. | yes |



## RStudio

## Jupyter

| Template | Description | Continuous testing |
| -------- | ----------- | ------------------ |
| `jupyterhub.yml` | Perform the deployment of a JupyterHub server starting from a clean Ubuntu 22.04 (Live Build). | yes |

## Deploy a VM

## Utils

| Template | Description | Continuous testing |
| -------- | ----------- | ------------------ |
| `nfs.yml` | Deploy a cluster of VMs, with nfs share. | yes |
| `htcondor.yml` | Deploy a cluster of VMs, with HTCondor and nfs share. | yes |
| `irida.yml` | Deploy IRIDA lims | no (Unmaintained) |
