# VerticalScaleUp
PowerShell Azure Runbook to automate scaling between App Service plan pricing tiers.

Please, check tier levels and their order in array `$tierLevels` and adjust them according to your needs.
Under [this link](https://github.com/MicrosoftDocs/azure-docs-powershell/blob/master/azurermps-4.4.1/AzureRM.Websites/Set-AzureRmAppServicePlan.md) you can find description of `-Tier` and `-WorkerSize` arguments, which you can use when adjusting configuration.

# Reliability
Please, be advised, that I tested the runbook up to S3 tier and I can't guarantee it will work will properly work with Premium tiers.

# Further reference
This runbook is part of my blogpost about automating vertical scalling, which you can find here (it's in polish): [https://grzegorzpawlowski.pl/autoscale-scale-up-vertical-runbook](https://grzegorzpawlowski.pl/autoscale-scale-up-vertical-runbook)
