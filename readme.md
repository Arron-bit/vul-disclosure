# Prism Vulnerability Disclosure

This repository tracks the disclosure status of 15 previously unknown security vulnerabilities discovered by **Prism**, an LLM-assisted gray-box fuzzing framework for web applications.

All vulnerabilities were responsibly disclosed to the respective maintainers. This page will be continuously updated with CVE identifiers and patch links as they become available.

## Discovered Vulnerabilities

| # | Application | Type | Status | CVE | Reference |
|---|------------|------|--------|-----|-----------|
| 1 | Apache Solr | XXE | Submitted | Pending | Internal Issue |
| 2 | OpenMRS | PT | Patched | CVE-2026-40076 | [Commit 6b392f6](https://github.com/openmrs/openmrs-core/commit/6b392f6) |
| 3 | OpenMRS | PT | Patched | CVE-2026-40075 | [Commit 52fd8bb](https://github.com/openmrs/openmrs-core/commit/52fd8bb) |
| 4 | Shopizer | PT | Submitted | CVE-2026-36767 | [Issue #1091](https://github.com/shopizer-ecommerce/shopizer/issues/1091) |
| 5 | Shopizer | PT | Submitted | CVE-2026-36768 | [Issue #1092](https://github.com/shopizer-ecommerce/shopizer/issues/1092) |
| 6 | Shopizer | XSS | Submitted | CVE-2026-36766 | [Issue #1093](https://github.com/shopizer-ecommerce/shopizer/issues/1093) |
| 7-10 | Halo | SSRF | Submitted | CVE-2026-36756---CVE-2026-36759 | Internal Issue |
| 11 | SpringBlade | SSRF | Submitted | CVE-2026-36764 | [Issue #36](https://github.com/chillzhuang/SpringBlade/issues/36) |
| 12 | SpringBlade | XXE | Submitted | CVE-2026-36765 | [Issue #37](https://github.com/chillzhuang/SpringBlade/issues/37) |
| 13 | SpringBlade | XSS | Submitted | CVE-2026-36763 | [Issue #38](https://github.com/chillzhuang/SpringBlade/issues/38) |
| 14 | JeeSite | XSS | Submitted | CVE-2026-36761 | [Commit 6d07699](https://github.com/thinkgem/jeesite/commit/6d07699071d71829c585aa19f065e79f58264fb6) |
| 15 | JeeSite | PT | Submitted | CVE-2026-36762 | [Issue #529](https://github.com/thinkgem/jeesite/issues/529) |

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
| OpenMRS | Patched | CVE-2026-40075 CVE-2026-40076 | [6b392f6](https://github.com/openmrs/openmrs-core/commit/6b392f6), [52fd8bb](https://github.com/openmrs/openmrs-core/commit/52fd8bb) |
| Shopizer | Disclosed | CVE-2026-36766 CVE-2026-36767 CVE-2026-36768 | — |
| Halo | Disclosed | CVE-2026-36756 CVE-2026-36757 CVE-2026-36758 CVE-2026-36759 | — |
| SpringBlade | Disclosed | CVE-2026-36763 CVE-2026-36764 CVE-2026-36765 | — |
| JeeSite | Disclosed | CVE-2026-36761 CVE-2026-36762 | [6d07699](https://github.com/thinkgem/jeesite/commit/6d07699071d71829c585aa19f065e79f58264fb6) |

> **Last updated:** 2026-04-22

## Contact

For questions regarding these vulnerabilities, please contact  `jin2019@sjtu.edu.cn`.
