# terraform

downlaod azure cli and install it

https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli#run-the-azure-cli


go to portal.azure.com/

go to https://portal.azure.com/#view/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/

you note down the Tenant ID

az login --tenant <Tenant ID>
az login --tenant 0f152e3242ea-8f7d-42343242324e3-a047-9fb1d02342984f66


- For Azure CLI, use one of the commands az login, az account list, or az account tenant list. All of command's included below return the tenantId property for each of your subscriptions.

- run this command in azure cli

```
az account list
az account tenant list
```


- Get all subscriptions for a tenant.

```
az account subscription list
```

from visual studio code run the below command

```
az login --tenant 0f152234eea-8f7d-4423423223e3-a047-9fb1d0984f6623423432
```

got to learn.microsoft.com/en-us/azure/  --> any services --> go to quickstart --> terraform 