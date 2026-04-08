# Prism Vulnerability Disclosure

This repository tracks the disclosure status of 15 previously unknown security vulnerabilities discovered by **Prism**, an LLM-assisted gray-box fuzzing framework for web applications.

All vulnerabilities were responsibly disclosed to the respective maintainers. This page will be continuously updated with CVE identifiers and patch links as they become available.

## Discovered Vulnerabilities

| # | Application | Reference | Endpoint | Type | Impact |
|---|-------------|-----------|----------|------|--------|
| 1 | Apache Solr | Internal Issue | `POST /cluster/plugin` | UFU | Remote Code Execution |
| 2 | OpenMRS | [Commit 6b392f6](https://github.com/openmrs/openmrs-core/commit/6b392f6) | `POST /openmrs/ws/rest/v1/module` | PT | Remote Code Execution |
| 3 | OpenMRS | [Commit 52fd8bb](https://github.com/openmrs/openmrs-core/commit/52fd8bb) | `GET /openmrs/moduleResources/{moduleid}` | PT | Arbitrary File Read |
| 4 | Shopizer | Issue #1091 | `POST /api/v1/private/content/images/add` | PT | Remote Code Execution |
| 5 | Shopizer | Issue #1092 | `POST /api/v1/private/content/images/rename` | PT | Remote Code Execution |
| 6 | Shopizer | Issue #1093 | `POST /api/v1/private/content` | XSS | Credential Theft / Script Execution |
| 7 | Halo | Internal Issue | `POST /plugins/{name}/upgrade-from-uri` | SSRF | Internal Network Exposure |
| 8 | Halo | Internal Issue | `POST /plugins/-/install-from-uri` | SSRF | Internal Network Exposure |
| 9 | Halo | Internal Issue | `POST /themes/{name}/upgrade-from-uri` | SSRF | Internal Network Exposure |
| 10 | Halo | Internal Issue | `POST /themes/-/install-from-uri` | SSRF | Internal Network Exposure |
| 11 | SpringBlade | Issue #36 | `POST /ureport/datasource/testConnection` | SSRF | Arbitrary File Read |
| 12 | SpringBlade | Issue #37 | `POST /ureport/designer/saveReportFile` | XXE | Arbitrary File Read |
| 13 | SpringBlade | Issue #38 | `POST /api/blade-desk/notice/submit` | XSS | Credential Theft / Script Execution |
| 14 | JeeSite | Issue #528 | `POST /a/msg/msgInner/save` | XSS | Credential Theft / Script Execution |
| 15 | JeeSite | Issue #529 | `POST /a/file/upload` | PT | Remote Code Execution |

## Vulnerability Types

- **UFU**: Unsafe File Upload
- **PT**: Path Traversal
- **XXE**: XML External Entity
- **SSRF**: Server-Side Request Forgery
- **XSS**: Cross-Site Scripting

## Disclosure Status

| Application | Status | CVE ID | Patch |
|-------------|--------|--------|-------|
| Apache Solr | Confirmed, fix in progress | Pending | — |
| OpenMRS | Patched | Pending | [6b392f6](https://github.com/openmrs/openmrs-core/commit/6b392f6), [52fd8bb](https://github.com/openmrs/openmrs-core/commit/52fd8bb) |
| Shopizer | Disclosed | Pending | — |
| Halo | Disclosed | Pending | — |
| SpringBlade | Disclosed | Pending | — |
| JeeSite | Disclosed | Pending | — |

> **Last updated:** 2026-04-08

## Contact

For questions regarding these vulnerabilities, please contact the corresponding author at `houqinsheng@sjtu.edu.cn`.
