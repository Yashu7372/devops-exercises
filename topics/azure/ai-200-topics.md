# Azure AI-200 Course Topics

AI-200 (Developing AI Cloud Solutions on Azure) is an associate-level Microsoft exam for developers who build the back end of AI solutions on Azure. Third-party guides say it replaces AZ-204 and leads to the Azure AI Cloud Developer Associate certification; this was not confirmed on Microsoft Learn.

The target candidate contributes across the whole solution lifecycle: requirements gathering, design, development, deployment, security, monitoring and troubleshooting. Microsoft's skills-measured list was last updated 2026-04-15, per the search listing.

> **Caveat:** Microsoft Learn and the study-guide sites were blocked when this was written, so the content comes from search summaries, not the opened official page. Only the data-management weighting is confirmed.

## Skills measured

| Area | Weighting | Focus |
| --- | --- | --- |
| Containerized solutions | Not confirmed | Build and run AI workloads in containers |
| Data management | 25-30% | Data services that back AI solutions |
| Messaging and integration | Not confirmed | Wiring AI into a production application |
| Security and observability | Not confirmed | Secrets, configuration, monitoring |

## Topic breakdown

The grouping is approximate until checked against the official guide.

### Containerized solutions

- Azure Container Registry and ACR Tasks
- Containers on App Service
- Azure Container Apps, with KEDA-based scaling
- Deployments to Azure Kubernetes Service (AKS)

### Data management

- Azure Cosmos DB for NoSQL
- Azure Database for PostgreSQL with pgvector
- Azure Managed Redis

### Messaging and integration

- Azure Service Bus
- Azure Event Grid
- Azure Functions

### Security and observability

- Azure Key Vault
- Azure App Configuration
- OpenTelemetry
- Kusto Query Language (KQL) for log analysis

## Sources

- [Study guide for Exam AI-200 (Microsoft Learn)](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-200) - the authority for exact weightings and sub-topics
- [AI-200 Study Guide 2026 (mscertquiz)](https://mscertquiz.com/blog/ai-200-study-guide) - appeared in search results, not opened
- [AI-200 Free Study Guide (A Guide to Cloud & AI)](https://www.aguidetocloud.com/cert-tracker/ai-200/) - appeared in search results, not opened
