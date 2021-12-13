# Backup Azure DevOps repositories to Azure storage
Steps followed:
 1. Create a container in the Azure storage account.
 2. Generate a new PAT in Azure DevOps with 'Read' access to 'Code'
 3. Create a new Service connection in Azure DevOps to access the Azure subscription that contains the storage account.
 4. Create a YAML pipeline with the code here. 

Refer this link to know how to create a storage account in Azure Subscription
https://docs.microsoft.com/en-us/azure/storage/common/storage-account-create?tabs=azure-portal

Refer this link to know how to create a PAT in Azure DevOps
https://docs.microsoft.com/en-us/azure/devops/organizations/accounts/use-personal-access-tokens-to-authenticate?view=azure-devops&tabs=preview-page

Refer this link to know how to create a Service connection between Azure DevOps and Azure Subscription
https://docs.microsoft.com/en-us/azure/devops/pipelines/library/service-endpoints?view=azure-devops&tabs=yaml
