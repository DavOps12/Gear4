# Gear4
Repository per AZ-400

## AZ-400: Development for enterprise DevOps

### 1. Introduction to DevOps

#### Introduction
[What is DevOps](https://www.donovanbrown.com/post/what-is-devops)
[AZ-400 Certification exam](https://learn.microsoft.com/en-us/learn/certifications/exams/az-400)
[DevOps Foundation](https://go.microsoft.com/fwlink/?linkid=2268284)

#### Introduction to Azure Repos
[Azure DevOps on Microsoft Learn](https://learn.microsoft.com/en-us/azure/devops/repos)

#### Introduction to GitHub
[GitHub skills](https://skills.github.com/)


### 2. Plan Agile with GitHub Projects and Azure Boards



## AZ-400: Implement a secure continuous deployment using Azure Pipelines

### 1. Introduction to deployment patterns

#### Introduction to deployment patterns
[What are microservices](https://learn.microsoft.com/en-us/devops/deliver/what-are-microservices)


### 2. Implement blue-green deployment and feature toggles

#### Explore deployment slots
[Set up Staging Environments in Azure App Service](https://learn.microsoft.com/en-us/azure/app-service/deploy-staging-slots)

#### Introduction to feature toggles
[Explore how to progressively expose your features in production for some or all users](https://learn.microsoft.com/en-us/azure/devops/articles/phase-features-with-feature-flags)

#### Describe feature toggle maintenance
[Azure App Configuration offers a Feature Manager](https://learn.microsoft.com/en-us/azure/azure-app-configuration/manage-feature-flags)


### 3. Implement canary releases and dark launching

#### Examine traffic manager
[What is Traffic Manager?](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview)
[How Traffic Manager works](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-how-it-works)
[Traffic Manager Routing Methods](https://learn.microsoft.com/en-us/azure/traffic-manager/traffic-manager-routing-methods)


### 4. Implement A/B testing and progressive exposure deployment

#### Explore CI-CD with deployment rings
[Explore how to progressively expose your Azure DevOps extension releases in production to validate before impacting all users](https://learn.microsoft.com/en-us/azure/devops/articles/phase-rollout-with-rings)


### 5. Integrate with identity management systems

#### Explore workload identities
[App Objects and Service Principals](https://learn.microsoft.com/en-us/entra/identity-platform/app-objects-and-service-principals)

#### Implement managed identities
[What are managed identities for Azure Resources](https://learn.microsoft.com/en-us/entra/identity/managed-identities-azure-resources/overview)
[Use an Azure Resource Manager service connection](https://learn.microsoft.com/en-us/azure/devops/pipelines/library/connect-to-azure)
[Set a Resource Manager workload identity service connection](https://learn.microsoft.com/en-us/azure/devops/pipelines/release/configure-workload-identity)
[Configuring OpenID Connect in Azure](https://docs.github.com/en/actions/deployment/security-hardening-your-deployments/configuring-openid-connect-in-azure)


### 6. Manage application configuration data

#### Integrate Azure Key Vault with Azure Pipelines
[What is Azure Keyvault](https://learn.microsoft.com/en-us/azure/key-vault/key-vault-overview)



##  AZ-400: Manage infrastructure as code using Azure and DSC

### 1. Explore infrastructure as code and configuration management

#### Understand idempotent configuration
[idempotency for windows azure message queues](https://www.atmosera.com/blog/idempotency-for-windows-azure-message-queues/)
[Create target Environment](https://learn.microsoft.com/en-us/azure/devops/pipelines/process/environments)
[What is IaC](https://learn.microsoft.com/en-us/devops/deliver/what-is-infrastructure-as-code)


### 2. Create Azure resources using Azure Resource Manager templates

#### Manage secrets in templates
[Azure Key Vault to pass secure parameter values during deployment](https://learn.microsoft.com/en-us/azure/azure-resource-manager/resource-manager-keyvault-parameter)
[Integrate ARM templates with Azure Pipelines](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/add-template-to-azure-pipelines)


### 3. Create Azure resources using Azure CLI

#### Install Azure CLI
[Sign in interactively](https://learn.microsoft.com/en-us/cli/azure/authenticate-azure-cli-interactively)
[Sign in with a managed identity](https://learn.microsoft.com/en-us/cli/azure/authenticate-azure-cli-managed-identity)
[Sign in using a service principal](https://learn.microsoft.com/en-us/cli/azure/authenticate-azure-cli-service-principal)


### 4. Explore Azure Automation with DevOps

#### Introduction
[Azure Automation State Configuration](https://learn.microsoft.com/en-us/azure/automation/automation-dsc-overview)
[Azure Update Manager](https://learn.microsoft.com/en-us/azure/update-manager/overview)
[Source Control Integration in Azure Automation](https://learn.microsoft.com/en-us/azure/automation/automation-dsc-overview)

#### Create automation accounts
[Create an Azure Automation account](https://learn.microsoft.com/en-us/azure/automation/quickstarts/create-azure-automation-account-portal)

#### Examine webhooks
[Starting an Azure Automation runbook with a webhook](https://learn.microsoft.com/en-us/azure/automation/automation-webhooks)

#### Create a workflow
[Tutorial: Create a PowerShell Workflow runbook in Automation](https://learn.microsoft.com/en-us/azure/automation/learn/automation-tutorial-runbook-textual)


### 5. Implement Desired State configuration (DSC)

#### Understand configuration drift
[Windows PowerShell Desired State configuration overview](https://learn.microsoft.com/en-us/powershell/scripting/dsc/overview?view=powershell-7.4)
[Azure policy](https://azure.microsoft.com/services/azure-policy/)

#### Examine DSC configuration file
[DSC Configurations](https://learn.microsoft.com/en-us/powershell/dsc/configurations/configurations?view=dsc-1.1)
[DSC Resources](https://learn.microsoft.com/en-us/powershell/dsc/resources/resources?view=dsc-1.1)

#### Implement DSC and Linux Automation on Azure
[Get started with Desired State Configuration (DSC) for Linux](https://learn.microsoft.com/en-us/powershell/scripting/dsc/getting-started/lnxgettingstarted)


### 6. Implement Bicep

#### What is Bicep?
[What is Bicep?](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/overview)

#### Understand Bicep file structure and syntax
[Parameters in Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/parameters/)
[Variables in Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/variables)
[Resource declaration in Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/resource-declaration/)
[Using modules in Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/modules/)
[Outputs in Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/outputs/)
[Best practices for Bicep](https://learn.microsoft.com/en-us/azure/azure-resource-manager/bicep/best-practices)



## AZ-400: Design and implement a dependency management strategy

### 1. Explore package dependencies

#### Understand source and package componentization
[Azure Artifacts best practices](https://learn.microsoft.com/en-us/azure/devops/artifacts/concepts/best-practices?view=azure-devops)


### 2. Understand package management

#### Explore packages
[An introduction to NuGet](https://learn.microsoft.com/en-us/nuget/what-is-nuget)
[About packages and modules](https://docs.npmjs.com/about-packages-and-modules)

#### Consume packages
[Upstream sources](https://learn.microsoft.com/en-us/azure/devops/artifacts/concepts/upstream-sources)
[Package graphs in Azure Artifacts](https://learn.microsoft.com/en-us/azure/devops/artifacts/concepts/package-graph?view=azure-devops)


### 3. Migrate consolidate and secure artifacts

#### Migrate and integrating artifact repositories
[Get started with NuGet packages in Azure Artifacts](https://learn.microsoft.com/en-us/azure/devops/artifacts/get-started-nuget?view=azure-devops&tabs=windows)

#### Examine permissions
[Secure and share packages using feed permissions.](https://learn.microsoft.com/en-us/azure/devops/artifacts/feeds/feed-permissions)
[Manage permissions](https://learn.microsoft.com/en-us/azure/devops/artifacts/feeds/feed-permissions?view=azure-devops&tabs=nuget%2Cnugetserver22%2Cnugetserver)


### 4. Implement a versioning strategy

#### Understand versioning of artifacts
[Publish NuGet packages with Azure Pipelines (YAML/Classic)](https://learn.microsoft.com/en-us/azure/devops/pipelines/artifacts/nuget?view=azure-devops&tabs=yaml#package-versioning)

#### Examine release views
[What are feed views?](https://learn.microsoft.com/en-us/azure/devops/artifacts/concepts/views?view=azure-devops)

#### Promote packages
[Promote packages and manage feed views](https://learn.microsoft.com/en-us/azure/devops/artifacts/feeds/views?view=azure-devops&tabs=nuget%2Cnugetserver22%2Cnugetserver%2Cpowershell)


### 5. Introduction to GitHub Packages

####
[]()



## AZ-400: Implement continuous feedback

### 1. Implement tools to track usage and flow

#### Introduction to continuous monitoring
[Release and work item insights](https://learn.microsoft.com/en-us/azure/azure-monitor/app/release-and-work-item-insights?tabs=continuous-monitoring)

#### Examine Kusto Query Language (KQL)
[KQL overview](https://learn.microsoft.com/en-us/kusto/query/?view=azure-data-explorer&preserve-view=true)

#### Explore Application Insights
[Smart detection in Application Insights](https://learn.microsoft.com/en-us/azure/azure-monitor/alerts/proactive-diagnostics)


### 3. Share knowledge within teams

#### Introduction to Azure DevOps project wikis
[Create a wiki](https://learn.microsoft.com/en-us/azure/devops/project/wiki/wiki-create-repo?view=azure-devops&tabs=browser)
[Edit a wiki](https://learn.microsoft.com/en-us/azure/devops/project/wiki/publish-repo-to-wiki)
[Mermaid](https://mermaid-js.github.io/mermaid/)

#### summary
[Azure Boards extensions](https://learn.microsoft.com/en-us/azure/devops/boards/extensions/migrate-integrate?view=azure-devops)


### 4. Design processes to automate application analytics

#### Explore IT Service Management Connector
[ITSMC overview](https://learn.microsoft.com/en-us/azure/azure-monitor/platform/itsmc-overview)



## AZ-400: Implement security and validate code bases for compliance

### 1. Introduction to Secure DevOps

#### Understand threat modeling
[Threat Modeling Tool feature](https://learn.microsoft.com/en-us/azure/security/azure-security-threat-modeling-tool-feature-overview)

#### Explore CodeQL in GitHub
[CodeQL overview](https://codeql.github.com/docs/codeql-overview/about-codeql/)


### 3. Software Composition Analysis

#### Implement GitHub Dependabot alerts and security updates
[About alerts for vulnerable dependencies](https://docs.github.com/free-pro-team@latest/github/managing-security-vulnerabilities/about-alerts-for-vulnerable-dependencies)
[About GitHub Dependabot security updates](https://docs.github.com/free-pro-team@latest/github/managing-security-vulnerabilities/about-github-dependabot-security-updates)


### 4. Security Monitoring and Governance

#### Examine Microsoft Defender for Cloud usage scenarios
[Microsoft Defender for Cloud planning and operations guide](https://learn.microsoft.com/en-us/azure/defender-for-cloud/security-center-planning-and-operations-guide)

#### Explore Azure policy
[Azure Policy Check Gate task](https://learn.microsoft.com/en-us/azure/devops/pipelines/tasks/deploy/azure-policy-check-gate)
[Azure Policy](https://azure.microsoft.com/services/azure-policy/)

#### Explore initiatives
[Azure Policy definition structure](https://learn.microsoft.com/en-us/azure/governance/policy/concepts/definition-structure)

#### Explore resource locks
[Lock your Azure resources to protect your infrastructure](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources?tabs=json)
