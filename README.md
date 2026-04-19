# Akamai API Security (akamai-api-security)
Akamai API Security (formerly Noname Security) provides comprehensive API discovery, posture management, and threat protection for organizations across cloud, on-premises, and hybrid environments. The platform continuously discovers and monitors all APIs, identifies vulnerabilities and misconfigurations, detects and responds to API threats in real time, and provides pre-production security testing integrated into CI/CD pipelines.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/akamai-api-security/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Discovery, API Security, Cloud Security, Posture Management, Runtime Protection, Threat Protection

## Timestamps

- **Created:** 2026-03-26
- **Modified:** 2026-04-19

## APIs

### Akamai API Security
Akamai API Security provides end-to-end API protection including discovery, posture management, runtime protection, and active testing.

**Human URL:** [https://www.akamai.com/products/api-security](https://www.akamai.com/products/api-security)

#### Tags:

 - API Discovery, API Security, Runtime Protection, Threat Protection

#### Properties

- [Documentation](https://techdocs.akamai.com/api-security/docs/welcome)
- [GettingStarted](https://techdocs.akamai.com/api-security/docs/get-started)
- [OpenAPI](openapi/akamai-api-security-openapi.json)

### Akamai APIs
Akamai provides a comprehensive set of REST APIs for managing and configuring their platform services using EdgeGrid authentication.

**Human URL:** [https://techdocs.akamai.com/home/page/products-tools-a-z](https://techdocs.akamai.com/home/page/products-tools-a-z)

#### Tags:

 - Configuration, EdgeGrid, Platform API, REST API

#### Properties

- [Documentation](https://techdocs.akamai.com/home/page/products-tools-a-z)
- [Authentication](https://techdocs.akamai.com/developer/docs/authenticate-with-edgegrid)
- [GettingStarted](https://techdocs.akamai.com/developer/docs/get-started)

## Common Properties

- [Website](https://www.akamai.com/products/api-security)
- [Documentation](https://techdocs.akamai.com)
- [Blog](https://www.akamai.com/blog)
- [Pricing](https://www.akamai.com/products/api-security#pricing)
- [Support](https://www.akamai.com/support)
- [Login](https://control.akamai.com)
- [SignUp](https://www.akamai.com/free-trials)
- [GitHubOrganization](https://github.com/akamai)
- [StatusPage](https://www.akamaistatus.com)
- [LinkedIn](https://www.linkedin.com/company/akamai-technologies)
- [X](https://twitter.com/Akamai)

## Features

| Name | Description |
|------|-------------|
| API Discovery | Automatically discovers all APIs including shadow, zombie, GenAI, LLM, and MCP server APIs across cloud, on-premises, and hybrid environments. |
| Posture Management | Audits APIs for vulnerabilities and misconfigurations including the full OWASP API Top 10, generating posture findings from runtime incidents. |
| Runtime Protection | Uses contextual insights to detect and block API threats including business logic abuse, credential attacks, data scraping, and malicious bots in real time. |
| CI/CD Security Testing | Runs 200+ dynamic security tests simulating OWASP API Top 10 attacks integrated into CI/CD pipelines without sacrificing development speed. |
| GitHub Integration | Automatically scans GitHub repositories for OpenAPI specs and adds them to the API library for security analysis and posture assessment. |
| App and API Protector Integration | Direct integration with Akamai App and API Protector for blocking API threats detected at runtime. |

## Use Cases

| Name | Description |
|------|-------------|
| Shadow API Discovery | Security teams automatically discover undocumented and shadow APIs across their environment to eliminate blind spots. |
| API Vulnerability Assessment | Security engineers assess API posture against OWASP API Top 10 and compliance frameworks to prioritize remediation. |
| Real-Time Threat Detection | SOC analysts detect and respond to API attacks, data leakage, and suspicious behavior in real time. |
| Pre-Production API Testing | Development teams integrate API security testing into CI/CD pipelines to find and fix vulnerabilities before production. |
| Compliance Reporting | Compliance teams assess API security posture against industry frameworks and generate audit-ready reports. |

## Integrations

| Name | Description |
|------|-------------|
| Akamai App and API Protector | Direct integration for blocking API threats detected by API Security |
| GitHub | Automatic OpenAPI spec discovery from GitHub repositories |
| CI/CD Pipelines | Integration with development pipelines for pre-production security testing |
| SIEM | Export security events to SIEM platforms for centralized monitoring |
| AWS Marketplace | Available on AWS Marketplace for cloud-native deployments |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Akamai API Security OpenAPI](openapi/akamai-api-security-openapi.json)

### JSON Schema

- 71 schema files in [json-schema/](json-schema/)

### JSON Structure

- 71 structure files in [json-structure/](json-structure/)

### JSON-LD

- [Akamai API Security Context](json-ld/akamai-api-security-context.jsonld)

### Examples

- 71 example files in [examples/](examples/)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [API Security](capabilities/shared/api-security.yaml) — 5 operations for Akamai Application Security configuration management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [API Security Management](capabilities/api-security-management.yaml) | Akamai API Security | 5 | Security Engineer, API Security Analyst |

## Vocabulary

- [Akamai API Security Vocabulary](vocabulary/akamai-api-security-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 6 actions, 1 workflow, and 2 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Akamai API Security Spectral Rules](rules/akamai-api-security-spectral-rules.yml) — 22 rules across 9 categories enforcing Akamai API Security conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
