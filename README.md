## Azure DevOps Labs

### Goal
In this lab you will take a dotNet application and sprinkle a bit of DevOps on it.
We will import the code to our own Azure DevOps Git repository, set up version control policies to manage changes and then configure automated continuous integration and delivery to ultimately see the application running in "production".
Some of the highlights include setting up build and release pipelines in Azure DevOps, containerising a dotnet core application and deploying it to a Linux based Azure Web App
                
### High level steps
1)	Register a free Azure DevOps organization
2)	Configure Azure Environment (Azure Container Registry)
3)	Import and manage GIT repositories
4)	Setup a build and release pipelines
5)	Deploy and run Container image in an Azure Environment

### Requirements
You will need a Azure Subscription ( you can start with a 12 months free subscription here : https://azure.microsoft.com/en-us/free/ )

### Outcomes
After this session you will be familiar with Azure DevOps, be able to quickly and easily setup basic build and release pipelines and understand what it takes to do automated deployments into Azure.

### Let's get started
1. [Setup](./HOL/1.Setup.md)
2. [Build](./HOL/2.BuildDefinition.md)
3. [Release](./HOL/3.ReleaseTemplate.md)

### Tailpiece
This lab will walk you through the steps from start to finish, but of you want a quick and easy overview, take a look at the [Azure DevOps Project](https://docs.microsoft.com/en-us/azure/devops-project/azure-devops-project-ruby)
