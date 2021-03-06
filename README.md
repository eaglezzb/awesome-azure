![](img/azure-logo.png)

# awesome-azure

A curated list of awesome Microsoft Azure tools, guides, tutorials.

## Contributing

Please send a pull request to contribute. Your contributions are welcomed! Make sure you check out the the [Markdown Syntax](https://guides.github.com/features/mastering-markdown/)
guide and add the link you want to contribute in alphabetical order. 

## Table of Contents

- [SDKs](#sdks)
  - [Azure REST APIs](#azure-rest-apis)
  - [.NET](#net-sdk)
  - [Python](#python-sdk)
  - [Java](#java-sdk)
  - [Go](#go-sdk)
  - [Ruby](#ruby-sdk)
  - [Node.js](#nodejs-sdk)
  - [PHP](#php-sdk)
- [Command Line Tools](#command-line-tools)
  - [Azure Cross-Platform CLI](#azure-cross-platform-cli)
  - [Azure PowerShell](#azure-powershell)
  - [Azure CLI (:new::new:)](#azure-cli-newnew)
- [Services](#services)
  - [Storage](#storage)
  - [Virtual Machines](#virtual-machines)
- [Azure Resource Manager](#azure-resource-manager)
  - [Templates](#templates)
- [DevOps Tools](#devops-tools)
  - [Docker](#docker)
  - [Kubernetes](#kubernetes)
  - [Packer](#packer)
  - [Ansible](#ansible)
  - [Terraform](#terraform)
- Learning Resources
- Support
- Contact

## SDKs

### Azure REST APIs

- [Azure API Reference](https://msdn.microsoft.com/en-us/library/azure/mt420159.aspx)
- [azure-rest-api-specs](https://github.com/Azure/azure-rest-api-specs/)
- (article) [Authenticating to Azure APIs with Service Principal Accounts](https://github.com/Azure/azure-sdk-for-node/blob/master/Documentation/Authentication.md)

### .NET SDK

- [Repo](https://github.com/Azure/azure-sdk-for-net)
- [Install](https://azure.microsoft.com/en-us/documentation/api/)
- [Docs](https://azure.microsoft.com/en-us/documentation/articles/dotnet-sdk/)
- [Learn more](https://azure.microsoft.com/en-us/develop/net/)

### Python SDK

- [Repo](https://github.com/Azure/azure-sdk-for-python)
- [Docs and Samples](https://azure.microsoft.com/en-us/develop/python/)

### Java SDK

- [Repo](https://github.com/Azure/azure-sdk-for-java)
- [Install](https://azure.microsoft.com/en-us/documentation/articles/java-download-azure-sdk/)
- [Docs and Samples](https://azure.microsoft.com/en-us/develop/java/)

### Go SDK

- [Repo](https://github.com/Azure/azure-sdk-for-go)
- [Docs](https://github.com/Azure/azure-sdk-for-go/blob/master/README.md)

### Ruby SDK

- [Repo](https://github.com/Azure/azure-sdk-for-ruby)
- [Docs](https://azure.microsoft.com/en-us/develop/ruby/)
- [Samples](https://azure.microsoft.com/en-us/documentation/articles/?platform=ruby)

### Node.js SDK

- [Repo](https://github.com/Azure/azure-sdk-for-node)
- [Docs](https://azure.github.io/azure-sdk-for-node/)
- [Learn More](https://azure.microsoft.com/en-us/develop/nodejs/)

### PHP SDK

- [Repo](https://github.com/Azure/azure-sdk-for-php)
- [Docs and Samples](https://azure.microsoft.com/en-us/develop/php/)


## Command Line Tools

### Azure Cross-Platform CLI

- [Repo](https://github.com/Azure/azure-xplat-cli)
- [Install](https://azure.microsoft.com/en-us/documentation/articles/xplat-cli-install/)

### Azure PowerShell

- [Repo](https://github.com/azure/azure-powershell)
- [Install](https://azure.microsoft.com/en-us/documentation/articles/powershell-install-configure/)
- [Docs](https://msdn.microsoft.com/library/windowsazure/jj554330.aspx)

### Azure CLI (:new::new:)

- [Repo](https://github.com/Azure/azure-cli)
- [Install](https://github.com/Azure/azure-cli/blob/master/doc/preview_install_guide.md)

## Services

### Storage

Microsoft:

- [Azure Storage Explorer](http://storageexplorer.com/) – closed source, old version [open source](https://github.com/azure-storage/deco/releases)

Community:

- [ahmetalpbalkan/azurefs](https://github.com/ahmetalpbalkan/azurefs) – mount Azure Blob Storage as drives on Linux via FUSE

### Virtual Machines

Microsoft:

- [azure-vhd-utils](https://github.com/microsoft/azure-vhd-utils) – CLI utility to upload and inspect VM disks

## Azure Resource Manager

### Templates

Microsoft:

- [azure-quickstart-templates](https://github.com/Azure/azure-quickstart-templates) - gallery for ready-to-deploy ARM templates

Community:

- [AzureResourceVisualizer](https://github.com/ytechie/AzureResourceVisualizer) - visualizer for ARM templates: [armviz.io](http://armviz.io/)
- [Sublime-AzureResourceManager](https://github.com/GillesZunino/Sublime-AzureResourceManager/) - SublimeText plugin for ARM templates
- [vscode-arm](https://marketplace.visualstudio.com/items?itemName=msazurermtools.azurerm-vscode-tools) - VS Code plugin for ARM templates
- [vscode-armsnippet](https://marketplace.visualstudio.com/items?itemName=artofshell.armsnippet) - ARM template snippets for VS Code


## DevOps Tools

### Docker

- [docker-machine for Azure](https://docs.docker.com/machine/drivers/azure/) - create Docker VMs on Azure Resource Manager
- [docker-registry for Azure](https://docs.docker.com/registry/storage-drivers/azure/) - configure docker-registry to save images in Azure Blob Storage
- [azurefile-dockervolumedriver](https://github.com/Azure/azurefile-dockervolumedriver) - volume plugin for using Azure File Storage for persistent volumes
- Article: [Deploying Private Docker Registry on Azure](https://azure.microsoft.com/en-us/documentation/articles/virtual-machines-linux-docker-registry-in-blob-storage/)
- Article: [Docker Swarm mode on Azure Container Service](https://azure.microsoft.com/en-us/documentation/articles/container-service-docker-swarm/)
