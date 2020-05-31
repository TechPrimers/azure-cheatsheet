# Azure Cheatsheet
This is a cheatsheet for Azure commands
- [General](#general)
- [AKS](#aks)

## General Resources
- ResourceGroup - similar to project in GCP

## AKS 
### Get Credentials 
`az aks get-credentials --resource-group techprimers-group --name techprimers-cluster`

### Link Azure Container Registry
`az aks update -n techprimers-cluster -g techprimers-group --attach-acr techprimers`
