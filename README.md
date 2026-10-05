# Awesome Developer Security

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of security tools, libraries, frameworks, standards, and resources for modern software development.

## Contents

* [Introduction](#introduction)
* [Curation Criteria](#curation-criteria)
* [Secure Coding & Application Security](#secure-coding--application-security)
* [Secrets & Credential Detection](#secrets--credential-detection)
* [Dependency & Software Supply Chain Security](#dependency--software-supply-chain-security)
* [Infrastructure, Cloud & Container Security](#infrastructure-cloud--container-security)
* [CI/CD & Developer Workflow Security](#cicd--developer-workflow-security)
* [Standards, Frameworks & Learning](#standards-frameworks--learning)
* [Contributing](#contributing)
* [License](#license)

## Introduction

Developer security covers the practices and tools used to identify, prevent, and manage security risks throughout the software development lifecycle.

This list focuses on resources that are directly useful to developers and software teams, including secure coding guidance, application security testing, secret detection, dependency security, software supply-chain security, infrastructure security, and security-focused development workflows.

The goal is **curation rather than collection**: fewer useful resources are preferred over a large number of repetitive or low-quality entries.

## Curation Criteria

Resources are considered for inclusion based on:

* Direct relevance to software development or developer security.
* Technical usefulness and practical value.
* Documentation quality.
* Maintenance and project activity.
* Open-source status and licensing where applicable.
* Community adoption or ecosystem relevance.
* Distinctive capabilities or use cases.
* Whether the resource provides value not already covered by another entry.

Popularity alone is not sufficient for inclusion.

Archived, abandoned, deprecated, misleading, duplicate, or poorly documented resources are generally excluded.

Commercial or proprietary resources may be included when they provide significant value to developers and clearly belong within the scope of developer security.

## Secure Coding & Application Security

* [CodeQL](https://github.com/github/codeql) - Semantic code analysis engine used to query source code for security vulnerabilities and other coding problems.
* [OWASP Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/) - Framework for defining and verifying application-security requirements.
* [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) - Collection of practical guidance for implementing common application-security controls and secure development practices.
* [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/) - Comprehensive guidance for testing the security of web applications and services.
* [Semgrep](https://github.com/semgrep/semgrep) - Static analysis tool that uses code patterns and rules to identify bugs and security issues across multiple programming languages.

## Secrets & Credential Detection

* [detect-secrets](https://github.com/Yelp/detect-secrets) - Secret detection tool designed to prevent new secrets from entering a codebase while helping teams manage existing findings.
* [git-secrets](https://github.com/awslabs/git-secrets) - Git hook-based tool that prevents committing credentials and other sensitive information.
* [Gitleaks](https://github.com/gitleaks/gitleaks) - Secret scanner for detecting passwords, API keys, tokens, and other credentials in Git repositories, files, and input streams.
* [GitShield](https://github.com/Shigosag/GitShield) - Go CLI security engine for detecting leaked secrets, auditing package vulnerabilities through OSV.dev, and enforcing Git pre-commit and pre-push hooks.
* [Secretlint](https://github.com/secretlint/secretlint) - Pluggable linting tool for detecting credentials and integrating secret checks into development workflows.
* [TruffleHog](https://github.com/trufflesecurity/trufflehog) - Secret-scanning tool for discovering credentials and sensitive information in source repositories and related data.

## Dependency & Software Supply Chain Security

* [Cosign](https://github.com/sigstore/cosign) - Tool for signing and verifying software artifacts and container images using Sigstore.
* [Dependabot](https://github.com/dependabot/dependabot-core) - Dependency update tooling that creates updates for vulnerable and outdated dependencies across supported ecosystems.
* [Grype](https://github.com/anchore/grype) - Vulnerability scanner for container images and filesystems.
* [OpenSSF Malicious Packages](https://github.com/ossf/malicious-packages) - Collection of reports describing malicious packages found in open-source package repositories.
* [OpenSSF Package Analysis](https://github.com/ossf/package-analysis) - Project that analyzes package behavior to identify potentially malicious activity in open-source ecosystems.
* [OpenSSF Scorecard](https://github.com/ossf/scorecard) - Automated checks for evaluating security practices and supply-chain risks in open-source projects.
* [OSV Schema](https://github.com/ossf/osv-schema) - Machine-readable vulnerability schema for describing vulnerabilities affecting open-source package versions and commits.
* [OSV-Scanner](https://github.com/google/osv-scanner) - Vulnerability scanner that checks project dependencies against the Open Source Vulnerabilities database.
* [SLSA](https://github.com/slsa-framework/slsa) - Security framework for improving software supply-chain integrity from source to produced artifacts.

## Infrastructure, Cloud & Container Security

* [Checkov](https://github.com/bridgecrewio/checkov) - Policy-as-code scanner for identifying security and compliance problems in infrastructure-as-code and related resources.
* [KICS](https://github.com/Checkmarx/kics) - Open-source scanner for detecting security vulnerabilities, compliance issues, and infrastructure misconfigurations in infrastructure-as-code.
* [KubeLinter](https://github.com/stackrox/kube-linter) - Static analysis tool for checking Kubernetes YAML, Helm charts, and Kustomize manifests against security and operational best practices.
* [Trivy](https://github.com/aquasecurity/trivy) - Security scanner for vulnerabilities, misconfigurations, secrets, and software bills of materials across containers, filesystems, Git repositories, Kubernetes, and other targets.

## CI/CD & Developer Workflow Security

* [GitHub Code Security](https://docs.github.com/en/code-security) - GitHub documentation covering code scanning, dependency security, secret protection, and other software-security capabilities.
* [GitHub Secret Scanning](https://docs.github.com/en/code-security/concepts/secret-security/secret-scanning) - GitHub security feature for detecting exposed credentials and other supported secrets in repositories and related GitHub content.
* [StepSecurity Secure Repo](https://github.com/step-security/secure-repo) - Repository automation and guidance for applying security best practices to GitHub Actions workflows and repositories.

## Standards, Frameworks & Learning

* [CWE](https://cwe.mitre.org/) - Community-developed taxonomy of common weaknesses found in software and hardware.
* [NIST Secure Software Development Framework](https://csrc.nist.gov/projects/ssdf) - Framework of practices for reducing software vulnerabilities throughout the software development lifecycle.
* [OpenSSF](https://openssf.org/) - Open-source initiative focused on improving the security of the software supply chain.
* [OWASP](https://owasp.org/) - Open community providing application-security standards, guidance, documentation, tools, and educational resources.
* [OWASP Top 10](https://owasp.org/www-project-top-ten/) - Awareness document describing important categories of web application security risks.

## Contributing

Contributions are welcome when they improve the quality of the list.

Before opening a pull request:

1. Check that the resource is directly relevant to developer security.
2. Search the list to make sure it is not already included.
3. Verify the official repository or website.
4. Check that the project is maintained and documented.
5. Explain why the resource belongs on this list.
6. Use the existing entry format.
7. Keep descriptions concise, factual, and objective.
8. Avoid promotional language.
9. Do not submit duplicate resources that provide substantially the same purpose as an existing entry.
10. Make sure links work and point to canonical sources.

A resource may be rejected even if it is popular when it does not provide enough distinct value for this list.

For substantial changes, opening an issue before a pull request can help avoid duplicated work.

## License

This list is dedicated to the public domain under the [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/) license.
