# Azure Migrate

## Notes

- Software inventory must be performed to discover SQL Server instances and ASP.NET web apps.
- Please allow web apps and SQL discovery to run for sometime before creating assessments for Azure App Service or Azure SQL. If the discovery of web apps and SQL Server instances and databases is not allowed to complete, the respective instances are marked as Unknown in the assessment report.
- If using domain accounts, the appliance must be domain joined

## Additional Resources

- Azure Migrate
  - [YouTube | Thomas Maurer | Migrate servers to Azure using Azure Migrate][6]
- Discover
  - [MS | docs | Tutorial: Discover servers running in a VMware environment with Azure Migrate][2]
  - [MS | docs | Discover web apps and SQL Server instances in an existing project][5]
  - [MS | docs | Provide server credentials to discover software inventory, dependencies, web apps, and SQL Server instances and databases][3]
- Assess
  - App Service (app)
  - [MS | docs | Tutorial: Assess ASP.NET web apps for migration to Azure App Service][4]

[1]: ./examples/examples.bicep
[2]: https://docs.microsoft.com/en-us/azure/migrate/tutorial-discover-vmware
[3]: https://docs.microsoft.com/en-us/azure/migrate/add-server-credentials
[4]: https://docs.microsoft.com/en-us/azure/migrate/tutorial-assess-webapps
[5]: https://docs.microsoft.com/en-us/azure/migrate/how-to-discover-sql-existing-project
[6]: https://www.youtube.com/watch?v=yOKjbqbyF4A&ab_channel=ThomasMaurer
