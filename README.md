# TOSCA templates

TOSCA template for Laniakea

## Galaxy

| Template | Description | Continuous testing |
| -------- | ----------- | ------------------ |
| `galaxy.yml` | Perform the deployment of a Galaxy starting from a clean Virtual Machine (Live Build). Only the Galaxy production environment is installed. | yes |
| `laniakea-galaxy-express.yml` | Perform the deployment of a Galaxy starting from a cloud image with Galaxy and all its companion software already installed (Express Build). The template integrate also the possibilty to encrypt the persistent volume, save user credentials on Vault, and the installation of Laniakea Utils API. | yes |



## RStudio

## Jupyter

## Deploy a VM

## Utils

`nfs.yml`: deploy a cluster of VMs, with nfs share.

`irida.yml`: Deploy IRIDA lims (Unmaintained)
