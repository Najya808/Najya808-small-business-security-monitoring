# Small Business Security Monitoring System

## 1. Project Overview

This project focuses on designing and implementing a Security Information and Event Management (SIEM) environment using Wazuh.

The purpose is to demonstrate how a small business can monitor endpoint activity, identify suspicious security events, maintain file integrity visibility and review potential vulnerabilities through a centralised security monitoring platform.

This project is being developed as a practical cybersecurity portfolio project.

## 2. Problem Statement

Small businesses may lack dedicated security teams and centralised monitoring systems. As a result, suspicious endpoint activity, unexpected file changes and potential security weaknesses may go unnoticed.

This project explores how an open-source SIEM platform can provide centralised security visibility and support basic security investigations.

## 3. Project Objectives

- Deploy and configure a Wazuh monitoring environment.
- Connect and monitor Windows endpoints.
- Collect and analyse endpoint security events.
- Configure File Integrity Monitoring (FIM).
- Monitor authentication-related activity.
- Review endpoint vulnerability information.
- Investigate and document three security scenarios.
- Produce technical documentation and an executive summary.

## 4. Proposed Technology Stack

- SIEM Platform: Wazuh
- Endpoint: Windows 10
- Server environment: To be finalised
- Virtualisation: Oracle VirtualBox
- Operating system for Linux administration: Ubuntu 24.04 LTS
- Documentation and version control: GitHub

## 5. Proposed Architecture

The proposed environment consists of a monitored Windows endpoint, a Wazuh Manager, a Wazuh Indexer and a Wazuh Dashboard.

The Windows endpoint will run the Wazuh Agent to collect relevant security information. The manager will analyse incoming events and generate alerts. The indexer will store and index the alert data, while the dashboard will provide a central interface for monitoring and investigation.

The final deployment architecture will be updated after implementation.

## 6. Planned Security Investigations

1. Authentication Event Monitoring
2. File Integrity Monitoring
3. Vulnerability Visibility and Assessment

Each investigation will include its objective, test methodology, observed evidence, analysis and recommendations.

## 7. Expected Deliverables

- Working security monitoring environment.
- Endpoint integration documentation.
- Security monitoring and configuration evidence.
- Three documented security investigations.
- Architecture diagram.
- Technical report.
- Executive summary.
- GitHub portfolio documentation.

## 8. Project Scope and Ethical Considerations

All monitoring and testing will be performed on systems owned by the project developer or explicitly authorised for testing.

Simulated security events will be used where appropriate. Sensitive information, credentials and private logs will not be published.

The project demonstrates foundational security monitoring capabilities and does not claim to replace a professional managed security operations service.
