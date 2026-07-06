# Ben - Cyber Security Portfolio

## About

Cybersecurity practitioner focused on **Identity & Access Management
(IAM)** and **Security Operations (SOC)** with hands-on experience
building realistic enterprise security environments.

This portfolio demonstrates practical work across:

-   Identity lifecycle management
-   Authentication & access control
-   SIEM monitoring and investigation
-   Detection engineering
-   Incident response workflows
-   Security automation

------------------------------------------------------------------------

## Core Focus Areas

### Identity & Access Management

-   Identity Governance & Administration
-   SSO Federation (SAML 2.0 / OIDC)
-   Adaptive MFA & Conditional Access concepts
-   Joiner / Mover / Leaver (JML) automation
-   Access reviews and reporting
-   Identity API automation
-   Okta Workforce Identity

### Security Operations

-   Security monitoring & alert triage
-   Log analysis & event correlation
-   Incident investigation & reporting
-   Network and endpoint telemetry
-   Detection logic and KQL queries

------------------------------------------------------------------------

# Featured Projects

## 1. Okta Workforce Identity IAM Lab

**Objective**

Simulate an enterprise identity environment implementing SSO federation, adaptive MFA, identity lifecycle automation, SCIM 2.0 provisioning and API-driven access management.

**Objective**
Simulate an enterprise identity environment implementing SSO federation,
adaptive MFA, cross-directory identity lifecycle automation, SCIM 2.0
provisioning, and API-driven access management across Okta and Microsoft
Entra ID.

**Built:**

* Okta Workforce Identity environment as the source-of-truth directory
* SAML 2.0 federation with Salesforce Developer Edition
* OIDC authorization code flow using Node.js Express
* Adaptive MFA policies using network-based risk controls
* Full Joiner / Mover / Leaver automation across Okta and Microsoft Entra
  ID - Python, Okta REST API, and Microsoft Graph API
* SCIM 2.0 service provider built with Python FastAPI, receiving live
  provisioning from Okta
* Bulk reconciliation engine - desired-vs-actual state diffing with Graph
  `$batch`, dry-run safety, and protected-account scoping
* Access reporting, stale account detection, and policy-as-code exports

**Demonstrates:**

* Enterprise IAM architecture across two directories
* Authentication protocol understanding (SAML, OIDC, OAuth 2.0 client
  credentials)
* SCIM 2.0 provisioning protocol - implemented server-side
* Microsoft Graph API automation, throttling and eventual-consistency
  handling
* State reconciliation and drift detection
* Identity governance workflows and access lifecycle management
* Documented design decisions, known limitations, and defects found and
  fixed in live validation

[`Okta Workforce Identity Project`](https://github.com/bennhood/Okta-Workforce-Identity-Project)

<img width="959" height="224" alt="stack" src="https://github.com/user-attachments/assets/34ac52f1-69d5-4637-aec3-e7c65e00423c" />


------------------------------------------------------------------------

## 2. Azure: GeoIP Abuse Mapping & Open VM Honeypot

**Objective**

Simulate a publicly exposed asset and analyze real-world attack traffic.

**What This Demonstrates:**

-   Azure VM exposure & telemetry collection
-   Ingesting Windows Security Events into Sentinel
-   Mapping malicious IP addresses by geography
-   Identifying attack patterns via Event IDs
-   Writing KQL queries to isolate abuse signals

**Key Skills Shown:**

-   Threat visibility
-   Log interpretation
-   Practical SIEM usage
-   Documentation & reporting
-   Data enrichment

[`Azure SOC Honeypot GeoIP Abuse Map`](https://github.com/bennhood/Azure-SOC-Honeypot-GeoIP-Abuse-Map)

<img width="1361" height="213" alt="ServicesAzure" src="https://github.com/user-attachments/assets/3b048386-75df-4a21-b814-fffce15cf968" />


------------------------------------------------------------------------

## 3. Azure: SIEM Detection & Investigation Queries

**Objective**

Develop and document KQL queries used during SOC triage and
investigation.

**What This Demonstrates:**

-   Identifying suspicious authentication activity
-   Detecting brute force & failed login patterns
-   Checking privilege escalation indicators
-   Separating signal from noise

**Key Skills Shown:**

-   Analytical thinking
-   Query construction
-   SOC-style investigative flow

[`Azure Honeypot Brute Force Investigation`](https://github.com/bennhood/Azure-Honeypot-Brute-Force-Investigation-Incident-Closure)

<img width="1361" height="213" alt="ServicesAzure" src="https://github.com/user-attachments/assets/2ba65828-61ac-403b-984f-348464a31af0" />


------------------------------------------------------------------------

## 4. Splunk Firewall & SSH Log Dashboard

**Objective**

Design and implement Splunk dashboards to support SOC-style triage,
investigation, and prioritisation of firewall and SSH log activity.

**What This Demonstrates:**

-   Identifying suspicious traffic through volume-based heuristics
-   Detecting SSH brute force and reconnaissance behaviour
-   Enriching raw IP data with geolocation and reputation context
-   Applying layered analysis

**Key Skills Shown:**

-   SOC-oriented analytical thinking
-   Dashboard design
-   Threat context enrichment

[`Splunk Firewall & SSH Logs Dashboards`](https://github.com/bennhood/Splunk-Firewall-and-SSH-Logs-Dashboard)

------------------------------------------------------------------------

# Certifications

-   SC-300 Microsoft Certified: Identity and Access Administrator
-   SC-200 Microsoft Certified: Security Operations Analyst Associate
-   CompTIA Security+ SY0-701
-   Splunk Core Certified Power User

------------------------------------------------------------------------

# Current Focus

Building toward:

-   IAM Analyst
-   Security Operations Analyst
-   Identity Security Engineer

Focused on practical security projects that demonstrate operational
thinking.


------------------------------------------------------------------------

## Certifications (Click to verify)
<div>
  <a href="https://learn.microsoft.com/api/credentials/share/en-gb/benhood-3185/5CDA52090BA8825E?sharingId=1F70CA150F0A67F8">
    <img src="https://img.shields.io/badge/SC--300-0078D4?style=for-the-badge" /> </a>
  <a href="https://learn.microsoft.com/api/credentials/share/en-us/benhood-3185/129C7EF2BEFA20AB?sharingId=1F70CA150F0A67F8">
    <img src="https://img.shields.io/badge/SC--200-0078D4?style=for-the-badge" /> </a>
  <a href="https://www.credly.com/users/benjaminhood/badges#credly">
    <img src="https://img.shields.io/badge/-Security%2B-FF0000?&style=for-the-badge&logo=CompTIA&logoColor=white" /> </a>
  <a href="https://www.credly.com/users/benjaminhood/badges#credly">
    <img src="https://img.shields.io/badge/-Splunk%20Power%20User-000000?style=for-the-badge&logo=splunk&logoColor=white" /> </a>

</div>

------------------------------------------------------------------------

