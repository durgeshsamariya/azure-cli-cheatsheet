# Azure CLI 2.0 Cheatsheet

Azure CLI 2.0 cheatsheet for Login, Resources, VMs, Resource groups, Storage, Batch, and Containers.

## Logging in

### Login with web
```
az login
```

### Login in CLI
```
az login -u myemail@address.com
```

### List accounts
```
az account list
```

### Set subscription
```
az account set --subscription "xxx"
```

## Listing locations and resources / general

### List all locations
```
az account list-locations
```
