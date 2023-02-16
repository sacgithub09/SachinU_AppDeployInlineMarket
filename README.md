# SachinU_AppDeployInlineMarket

Steps to create sample app Visual Studio - create DotNet core application - hello world

Visual Studio - create ARM project Create ARM json for App Service Deploy Create ACR json - add ACR resource

Define azure-pipelines.yml - which includes steps for build app, publish Define Docker tasks - Build, Push, Publish, Copy Define Release stage Download the artifacts Create App Service Deploy App Service

Goto project settings - create Service Conn for ARM with subscription level access(name already defined in code - azureSubscription)

Setup build pipeline - select existing repos - select /azure-pipeline.yml --> run

This would run for 8-10mins - to create RG, App Service, Deploy

Goto portal.azure.com  - verify RG created in your subscription Under RG - you could see resources created and deployed

App Service Plan ACR App Service
