# Prism Vulnerability Disclosure

This repository tracks the disclosure status of 15 previously unknown security vulnerabilities discovered by **Prism**, an LLM-assisted gray-box fuzzing framework for web applications.

All vulnerabilities were responsibly disclosed to the respective maintainers. This page will be continuously updated with CVE identifiers and patch links as they become available.

## Discovered Vulnerabilities

| # | Application | Type | Status | CVE | Reference |
|---|------------|------|--------|-----|-----------|
| 1 | Apache Solr | XXE | Submitted | Pending | Internal Issue |
| 2 | OpenMRS | PT | Patched | Pending | [Commit 6b392f6](https://github.com/openmrs/openmrs-core/commit/6b392f6) |
| 3 | OpenMRS | PT | Patched | Pending | [Commit 52fd8bb](https://github.com/openmrs/openmrs-core/commit/52fd8bb) |
| 4 | Shopizer | PT | Submitted | Pending | [Issue #1091](https://github.com/shopizer-ecommerce/shopizer/issues/1091) |
| 5 | Shopizer | PT | Submitted | Pending | [Issue #1092](https://github.com/shopizer-ecommerce/shopizer/issues/1092) |
| 6 | Shopizer | XSS | Submitted | Pending | [Issue #1093](https://github.com/shopizer-ecommerce/shopizer/issues/1093) |
| 7-10 | Halo | SSRF | Submitted | Pending | Internal Issue |
| 11 | SpringBlade | SSRF | Submitted | Pending | [Issue #36](https://github.com/chillzhuang/SpringBlade/issues/36) |
| 12 | SpringBlade | XXE | Submitted | Pending | [Issue #37](https://github.com/chillzhuang/SpringBlade/issues/37) |
| 13 | SpringBlade | XSS | Submitted | Pending | [Issue #38](https://github.com/chillzhuang/SpringBlade/issues/38) |
| 14 | JeeSite | XSS | Submitted | Pending | [Issue #528](https://github.com/thinkgem/jeesite/issues/528) |
| 15 | JeeSite | PT | Submitted | Pending | [Issue #529](https://github.com/thinkgem/jeesite/issues/529) |

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

For questions regarding these vulnerabilities, please contact the corresponding author at `jin2019@sjtu.edu.cn`.
