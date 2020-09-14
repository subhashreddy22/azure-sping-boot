# azure-spring-boot

1. Add the azure maven webapp plugin
2. Run mvn azure-webapps:config to generate the necessary configuration like resource-group, app-name, region etc.
3. Login into Azure using command "az login" in Azure CLI
4. Deploy the app into Azure by running mvn azure-webapp:deploy
5. The above command creates a webapp, resource-group, service plan in Azure.
6. Logs can be tailed using the command "az webapp log tail --name azure-hello-world-test --resource-group azure-hello-world-rg" in Azure CLI