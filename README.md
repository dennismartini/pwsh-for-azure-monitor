#Parameters:

-subscriptionid #subscription id from azure

-resourcegroup #resource group of monitored resource

-resourceprovider #complete path to resource provider 

Example: If the complete path of your resource are "/subscriptions/#subscriptionid/resourceGroups/#resourcegroup/providers/Microsoft.Sql/servers/#sqlserver/databases/#sqldatabase", use only Microsoft.Sql/servers/#sqlserver/databases/#sqldatabase in this parameter. You can see this on Resource Explorer: https://resources.azure.com

-resourcename #the name of your resource

-metricname #the metric of  your resource (Like cpu_percent, AverageResponseTime or something like this)

-datametric #the received type of data (Like total, average, maximum, minimum)

-contextpath #the Azure Context previously saved in json format.
