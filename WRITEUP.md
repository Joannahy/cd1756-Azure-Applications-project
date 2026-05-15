# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

- using a Virtual Machine involves higher costs because resources must be allocated continuously, even when the application is idle, whereas App Service provides a more cost-efficient model by offering managed hosting with flexible pricing tiers. 
Regarding scalability: Virtual Machines require manual configuration to scale for creating additional instances, while App Service supports automatic scaling, making it easier to handle. 
Regarding availability: Virtual Machines require additional setup, such as availability sets or zones, to ensure reliability, while App Service includes built-in high availability and failover capabilities.

- I chose Azure App Service to deploy the application

- The application was deployed using Azure App Service after considering cost, scalability, availability, and workflow

### Assess app changes that would change your decision.

If the application requirements would change, for example if more control over the operating system, networking, or installed software would be needed, then a Virtual Machine would be better choice instead of App Service. This would also apply if the app needed any custom configurations, or more complex infrastructure management. In such cases, additional setup would be necessary and it is better to handle this with a VM.