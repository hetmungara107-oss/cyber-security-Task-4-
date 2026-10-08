# Task 3 - Basic Vulnerability Scan

## Cyber Security Internship

### Objective

The objective of this task was to perform a basic vulnerability assessment of my own PC using a free vulnerability scanning tool.

The scan was performed using OpenVAS / Greenbone Vulnerability Management (GVM) on Kali Linux.

## Tool Used

- Tool: OpenVAS / Greenbone Vulnerability Management
- Operating System: Kali Linux
- Target: My own Kali Linux PC
- Target IP: 10.42.42.161
- Scan Status: Completed

## Methodology

The following steps were performed:

1. Configured OpenVAS/GVM on Kali Linux.
2. Created a scan target for my local Kali Linux machine.
3. Configured the target using the local IP address.
4. Created a vulnerability scanning task.
5. Started the vulnerability scan.
6. Waited for the scan to complete.
7. Reviewed the generated report and results.
8. Analyzed the severity and Quality of Detection (QoD) of the results.
9. Documented the findings and their security significance.

## Scan Results

The scan completed successfully.

The scan reported four informational/log results:

| Finding | Severity | QoD |
|---|---|---|
| Traceroute | 0.0 (Log) | 80% |
| OS Detection Consolidation and Reporting | 0.0 (Log) | 80% |
| Hostname Determination Reporting | 0.0 (Log) | 80% |
| CPE Inventory | 0.0 (Log) | 80% |

### Vulnerability Summary

| Severity | Count |
|---|---:|
| Critical | 0 |
| High | 0 |
| Medium | 0 |
| Low | 0 |
| Log/Informational | 4 |

No CVEs were identified in this scan.

## Findings

### 1. Traceroute

Severity: 0.0 (Log)

The scanner generated traceroute information for the target system.

Risk: No security vulnerability was identified by this result.

Remediation: No specific remediation is required.

### 2. OS Detection Consolidation and Reporting

Severity: 0.0 (Log)

The scanner performed operating system detection and generated reporting information.

Risk: No security vulnerability was identified by this result.

Remediation: No specific remediation is required.

### 3. Hostname Determination Reporting

Severity: 0.0 (Log)

The scanner performed hostname determination and generated reporting information.

Risk: No security vulnerability was identified by this result.

Remediation: No specific remediation is required.

### 4. CPE Inventory

Severity: 0.0 (Log)

The scanner generated Common Platform Enumeration (CPE) inventory information for the target.

Risk: No security vulnerability was identified by this result.

Remediation: No specific remediation is required.

## Screenshots

The following screenshots are included as evidence:

- GVM dashboard
- Target configuration
- Completed vulnerability scan
- Scan results

## Security Assessment

The scan completed successfully and did not identify any Critical, High, Medium, or Low severity vulnerabilities.

The four reported results were informational/log results related to network and system identification.

It is important to note that a vulnerability scan result with no detected vulnerabilities does not guarantee that a system is completely secure. Regular updates, secure configurations, strong authentication, and periodic security assessments should still be maintained.

## Interview Questions

### 1. What is vulnerability scanning?

Vulnerability scanning is an automated process used to identify known security weaknesses, vulnerabilities, and potentially insecure configurations in a system.

### 2. What is the difference between vulnerability scanning and penetration testing?

Vulnerability scanning primarily identifies potential security weaknesses. Penetration testing goes further by safely attempting to validate whether identified weaknesses can actually be exploited and what impact they could have.

### 3. What are some common vulnerabilities in personal computers?

Common vulnerabilities include outdated software, missing security patches, weak configurations, unnecessary services, exposed network ports, and weak authentication.

### 4. How do scanners detect vulnerabilities?

Vulnerability scanners examine information such as services, software versions, configurations, and network responses and compare the information against known vulnerability and security information.

### 5. What is CVSS?

CVSS stands for Common Vulnerability Scoring System. It is a standardized system used to represent the severity of security vulnerabilities.

### 6. How often should vulnerability scans be performed?

Vulnerability scans should be performed regularly and after significant software, configuration, or infrastructure changes. They should also be performed when important new vulnerabilities are discovered.

### 7. What is a false positive in vulnerability scanning?

A false positive occurs when a scanner reports a possible vulnerability even though the vulnerability does not actually exist on the target system.

### 8. How do you prioritize vulnerabilities?

Vulnerabilities can be prioritized using factors such as severity, CVSS score, exploitability, system exposure, potential impact, and availability of remediation.

## Conclusion

This task provided practical experience with vulnerability scanning using OpenVAS/GVM. A vulnerability scan was successfully performed against my own Kali Linux PC.

The scan produced four informational/log results and did not identify any Critical, High, Medium, or Low severity vulnerabilities or CVEs.

The task helped demonstrate the basic concepts of vulnerability assessment, severity classification, CVSS, security findings, and remediation.
