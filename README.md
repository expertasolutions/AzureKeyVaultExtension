# Azure KeyVault Extension

![BuildStatus](https://dev.azure.com/experta/Community/_apis/build/status/expertasolutions.AzureKeyVaultExtension?branchName=master)

A set of Azure DevOps tasks to help with Azure KeyVault secrets creation and/or update. This extension is multiplatform compatible. See ***[Release notes](https://github.com/expertasolutions/AzureKeyVaultExtension/releases)***

# Tasks
## UploadMultipleAzureKeyVaultSecrets
![ManageKeyVaultSecrets](_screenShots/UploadMultipleAzureKeyVaultSecrets-v0.png)
#### Secrets file path (expected file format content)
```json
[
	{
		"secret": "my_first_secret",
		"value": "my_first_secret_value"
	},
	{
		"secret": "my_second_secret",
		"value": "my_second_secret_value"
	}
]
```
#### Important
*** Ensure that your subscription service principal have proper access policies rights on your Azure Key Vault ***

## CreateUpdateKeyVaultSecret
![ManageAzureKeyVaultSingleSecret](_screenShots/CreateUpdateKeyVaultSecret-v0.png)
#### Important
*** Ensure that your subscription service principal have proper access policies rights on your Azure Key Vault ***
