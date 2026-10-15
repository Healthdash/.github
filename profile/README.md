# Healthdash GitHub Organization profile

This repository contains organization-level information and links to the HealthDash ecosystem. This file is the GitHub org profile README (displayed from `.github/profile/README.md`).

Updated: 2026-10-15

## Homepage & Distribution

- Official product site: https://www.healthdash.lv
- Personalized Cloud Dashboard (PCD) (web UI): https://clouddashboard.healthdash.com
- Mobile app distribution: Google Play Store (see CloudDash-Frontend-JavaAndroid repository)
- CI/CD artifacts and releases: see each repository's Releases page and README for published artifacts (Docker images, static build artifacts, APK/AAB, CLI binaries).

## What each repository produces (artifacts and distribution channels)

- CloudDash-Frontend-ReactJS
  - Produces: static web application build (HTML, JS, CSS, assets) and versioned release bundles.
  - Distributed: served from https://clouddashboard.healthdash.com and associated CDN/hosting. Releases are published to GitHub Releases; CI publishes build artifacts to the release and to the deployment pipeline.
  - Tokenless repo badges (example):
    - [![Release](https://img.shields.io/github/v/release/Healthdash/CloudDash-Frontend-ReactJS?label=release)](https://github.com/Healthdash/CloudDash-Frontend-ReactJS/releases)
    - [![Last commit](https://img.shields.io/github/last-commit/Healthdash/CloudDash-Frontend-ReactJS)](https://github.com/Healthdash/CloudDash-Frontend-ReactJS/commits)
    - [![Open issues](https://img.shields.io/github/issues/Healthdash/CloudDash-Frontend-ReactJS)](https://github.com/Healthdash/CloudDash-Frontend-ReactJS/issues)

- CloudDash-Backend-ReactJS-API
  - Produces: backend service releases and Docker images used by staging/production.
  - Distributed: Docker images (internal registry), and GitHub Releases for source and artifacts. See repo README for registry coordinates.
  - Tokenless repo badges (example):
    - [![Release](https://img.shields.io/github/v/release/Healthdash/CloudDash-Backend-ReactJS-API?label=release)](https://github.com/Healthdash/CloudDash-Backend-ReactJS-API/releases)
    - [![Last commit](https://img.shields.io/github/last-commit/Healthdash/CloudDash-Backend-ReactJS-API)](https://github.com/Healthdash/CloudDash-Backend-ReactJS-API/commits)
    - [![Open issues](https://img.shields.io/github/issues/Healthdash/CloudDash-Backend-ReactJS-API)](https://github.com/Healthdash/CloudDash-Backend-ReactJS-API/issues)

- CloudDash-Frontend-JavaAndroid
  - Produces: Android application packages (APK / AAB) and signed release builds.
  - Distributed: Google Play Store (public/private tracks). CI produces signed artifacts attached to releases.
  - Tokenless repo badges (example):
    - [![Release](https://img.shields.io/github/v/release/Healthdash/CloudDash-Frontend-JavaAndroid?label=release)](https://github.com/Healthdash/CloudDash-Frontend-JavaAndroid/releases)
    - [![Last commit](https://img.shields.io/github/last-commit/Healthdash/CloudDash-Frontend-JavaAndroid)](https://github.com/Healthdash/CloudDash-Frontend-JavaAndroid/commits)
    - [![Open issues](https://img.shields.io/github/issues/Healthdash/CloudDash-Frontend-JavaAndroid)](https://github.com/Healthdash/CloudDash-Frontend-JavaAndroid/issues)

- CloudDash-Frontend-GoLangComponents
  - Produces: Go-based CLI tools and static binaries used in CI and admin tooling.
  - Distributed: release binaries attached to GitHub Releases and internal tooling registries.
  - Tokenless repo badges (example):
    - [![Release](https://img.shields.io/github/v/release/Healthdash/CloudDash-Frontend-GoLangComponents?label=release)](https://github.com/Healthdash/CloudDash-Frontend-GoLangComponents/releases)
    - [![Last commit](https://img.shields.io/github/last-commit/Healthdash/CloudDash-Frontend-GoLangComponents)](https://github.com/Healthdash/CloudDash-Frontend-GoLangComponents/commits)
    - [![Open issues](https://img.shields.io/github/issues/Healthdash/CloudDash-Frontend-GoLangComponents)](https://github.com/Healthdash/CloudDash-Frontend-GoLangComponents/issues)

- CloudDash-Frontend-PythonComponents
  - Produces: Python/Flask microservice packages and Docker images for optional extension services (PCD apps).
  - Distributed: Docker images, PyPI/internal package registry (when applicable), and GitHub Releases.
  - Tokenless repo badges (example):
    - [![Release](https://img.shields.io/github/v/release/Healthdash/CloudDash-Frontend-PythonComponents?label=release)](https://github.com/Healthdash/CloudDash-Frontend-PythonComponents/releases)
    - [![Last commit](https://img.shields.io/github/last-commit/Healthdash/CloudDash-Frontend-PythonComponents)](https://github.com/Healthdash/CloudDash-Frontend-PythonComponents/commits)
    - [![Open issues](https://img.shields.io/github/issues/Healthdash/CloudDash-Frontend-PythonComponents)](https://github.com/Healthdash/CloudDash-Frontend-PythonComponents/issues)

Note: exact artifact locations (S3 bucket paths, private Docker registry endpoints, signed APK URLs) are intentionally NOT listed here to avoid exposing sensitive infrastructure details. If you want exact internal URLs added, provide them through a secure channel and confirm they are safe to publish in this README.

## Communication & Collaboration channels (restored)

- Google Groups (customers / collaborators): https://groups.google.com/g/huaweihealthsyncv1y2022
- StackOverflow Teams (developer collaboration): https://stackoverflow.com/c/healthdash
- Keybase (development documentation & team): keybase://team/healthdash
- Wordpress (product blog / updates): https://linardsliepins.wordpress.com/
- Bitbucket (public bug tracker / legacy issues): https://bitbucket.org/HolimaX/sandboxandroid/issues/new

These channels are used for different audiences (customers, developers, testers). For private/professional support use organization-managed channels and request access if needed.

## CI / Build badges

The org profile will show tokenless, repository-level badges that do not embed service tokens. Reintroducing badges with tokens is not permitted here. Repository READMEs should maintain their own current CI badges. Example tokenless badges are included above for the main repos (release, last commit, open issues). If you want consistent badge styling across repositories, I can add a short badge guideline to this profile and optionally open PRs to each repository to add the badges in their READMEs.

## Support & Where to get help

- For bugs or feature requests: open an issue in the repository that best matches the component (example: https://github.com/Healthdash/CloudDash-Backend-ReactJS-API/issues).
- For cross-repo coordination or access requests: open an issue in this repository (https://github.com/Healthdash/.github/issues) with the details described below.
- For urgent production incidents: notify the on-call maintainer or organization owners via the organization incident channel.

## Maintainers & Access Instructions (updated)

Primary maintainer and organization owner:

- Linards Liepi4661 — @HolimaX — Primary maintainer / org owner — contact via GitHub.

How to request access or become a contributor:

1) Open an issue in the relevant repository or in this repository describing:
   - Your GitHub username
   - The resources you need access to (e.g., repo name, CI, Docker registry, Play Store)
   - The minimum access level required and why
   - Any timeframe or urgency
2) A repository owner or organization admin will respond to the issue with next steps. The typical response will either invite you to the organization/team or provide a temporary credential/process for the requested access.
3) For long-term access, an org admin will add you to the appropriate GitHub team with documented permissions.

If you are an org owner and want specific maintainer entries (GitHub handle + role + contact email) added here, provide the entries and I will update this profile.

## Compliance, standards and practices

- **WCAG 2.2 AA/AAA Accessibility & Digital Inclusion**:
  - Specification: [W3C WCAG 2.2 Recommendation](https://www.w3.org/TR/WCAG22/)
  - EU Harmonized Standard: [EN 301 549 V4.1.1](https://www.etsi.org/deliver/etsi_en/301500_301599/301549/) (Accessibility requirements for ICT products and services, implementing the European Accessibility Act Directive (EU) 2019/882 and Web Accessibility Directive (EU) 2016/2102)
  - US Standards: [Section 508](https://www.section508.gov/) (Rehabilitation Act, 36 CFR Part 1194) and ADA Title II/III digital accessibility guidelines
  - International / ISO Standard: [ISO/IEC 40500:2025](https://www.iso.org/standard/40500) (Information technology — W3C Web Content Accessibility Guidelines 2.2)
  - Ecosystem support: Implemented for the official product website (`www.healthdash.lv`), Personalized Cloud Dashboard (PCD web UI via `CloudDash-Frontend-ReactJS`), and the backend Admin Panel / Swagger API documentation (`CloudDash-Backend-ReactJS-API`).

- **camelCase & Software Construction Standards**:
  - Reference: [camelCase (Wikipedia)](https://en.wikipedia.org/wiki/Camel_case)
  - IEEE / ISO Standard: [ISO/IEC/IEEE 12207:2017](https://standards.ieee.org/ieee/12207/6888/) (Systems and software engineering — Software life cycle processes, Clause 6.4.5 Software Construction) and [IEEE 730-2014](https://standards.ieee.org/ieee/730/5082/) (IEEE Standard for Software Quality Assurance Processes)
  - Ecosystem support: Standardized across JavaScript/TypeScript (`CloudDash-Frontend-ReactJS`), Java/Kotlin (`CloudDash-Frontend-JavaAndroid`), and JSON REST API schema contracts (`CloudDash-Backend-ReactJS-API`).

- **SPDX license list & Software Bill of Materials (SBOM)**:
  - Reference: [SPDX license list](https://spdx.github.io/license-list-data)
  - ISO / International Standard: [ISO/IEC 5962:2021](https://www.iso.org/standard/81870.html) (Information technology — SPDX Specification V2.2.1)
  - US / EU Regulatory Alignment: Aligns with US Executive Order 14028 (Improving the Nation's Cybersecurity — SBOM mandates) and EU Cyber Resilience Act (CRA) component transparency requirements
  - Ecosystem support: Automated licensing audits, open-source compliance checks, and SBOM generation across all ecosystem repositories.

- **Semantic Versioning (SemVer 2.0.0)**:
  - Specification: [semver.org](https://semver.org/)
  - IEEE / ISO Standard: [IEEE 828-2012](https://standards.ieee.org/ieee/828/4890/) (IEEE Standard for Configuration Management in Systems and Software Engineering) and [ISO/IEC/IEEE 12207:2017](https://standards.ieee.org/ieee/12207/6888/) (Clause 6.4.10 Configuration Management Process)
  - Ecosystem support: Governs all repository tagging, GitHub Releases, Docker container image tagging, and Go CLI distribution.

- **OpenGraph & Semantic Web Metadata**:
  - Specification: [The Open Graph Protocol](https://www.opengraph.io/documentation)
  - W3C / Internet Standards: [W3C RDFa Core 1.1 Recommendation](https://www.w3.org/TR/rdfa-core/) and Schema.org metadata; IETF [RFC 8288](https://datatracker.ietf.org/doc/html/rfc8288) (Web Linking)
  - Ecosystem support: Embedded across PCD web app (`CloudDash-Frontend-ReactJS`) and public site (`www.healthdash.lv`) for rich link previews and search crawler indexing.

- **AMP (Accelerated Mobile Pages) & Web Performance**:
  - Reference: [amp.dev](https://www.amp.dev)
  - Standards: W3C Web Performance Working Group standards (Core Web Vitals, Navigation & Resource Timing) and IETF RFC 8164 / HTTP/2-HTTP/3 performance optimizations
  - Ecosystem support: Optimized delivery for landing pages and SER/FAQ documentation on mobile devices.

- **SPA (Single-Page Application)**:
  - Reference: [React glossary: SPA](https://reactjs.org/docs/glossary.html)
  - IEEE / ISO Standard: [ISO/IEC/IEEE 23026:2015](https://standards.ieee.org/ieee/23026/5638/) (Systems and software engineering — Engineering and management of websites for systems, software, and services information)
  - Ecosystem support: Architecture model for `CloudDash-Frontend-ReactJS` PCD interface.

- **PWA (Progressive Web Apps)**:
  - Reference: [MDN Progressive Web Apps](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps)
  - W3C Standards: [W3C Web Application Manifest](https://www.w3.org/TR/appmanifest/) and [W3C Service Workers](https://www.w3.org/TR/service-workers/)
  - Ecosystem support: Offline caching, service worker lifecycle, and installable experience in PCD web client.

- **Security certifications and hardening guidance**:
  - Guidance: [Ubuntu Security Certifications](https://ubuntu.com/security/certifications/docs)
  - EU Frameworks: [EU Cybersecurity Act (Regulation (EU) 2019/881)](https://eur-lex.europa.eu/eli/reg/2019/881/oj) (ENISA EUCC framework) and EU NIS2 Directive ([Directive (EU) 2022/2555](https://eur-lex.europa.eu/eli/dir/2022/2555/oj))
  - US Standards: [NIST SP 800-53 Rev. 5](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) (Security and Privacy Controls for Information Systems) and [FIPS 140-3](https://csrc.nist.gov/publications/detail/fips/140/3/final) (Cryptographic Modules)
  - IEEE / ISO Standards: [ISO/IEC 27001:2022](https://www.iso.org/standard/27001) (Information Security Management) and [IEEE 2883-2022](https://standards.ieee.org/ieee/2883/7201/) (Standard for Sanitizing Storage)
  - Ecosystem support: Hardened base Docker containers, CodeQL static code analysis, secrets scanning, and TLS 1.3 encryption across backend APIs.

- **Privacy regulations & Privacy Engineering**:
  - EU Regulation: EU GDPR ([Regulation (EU) 2016/679](https://gdpr.eu/what-is-gdpr/))
  - US Regulation: US CCPA/CPRA ([California Consumer Privacy Act](https://www.oag.ca.gov/privacy/ccpa)) and NIST Privacy Framework (NIST CSWP 29)
  - IEEE Standard: **[IEEE 7002-2022](https://standards.ieee.org/ieee/7002/6966/)** (IEEE Standard for Data Privacy Process — standardizing privacy-by-design, data protection impact assessments, and personal data management)
  - ISO/IEC Standards: [ISO/IEC 27701:2019](https://www.iso.org/standard/71670.html) (Privacy Information Management) and [ISO/IEC 29100:2024](https://www.iso.org/standard/83726.html) (Privacy framework)
  - Ecosystem support: End-to-end privacy engineering, granular user telemetry consent, secure health telemetry handling, and GDPR/CCPA data export and deletion endpoints.

- **UML 2.5 (Unified Modeling Language)**:
  - Reference: [UML 2.5 Diagrams](https://www.uml-diagrams.org/uml-25-diagrams.html)
  - ISO / IEC Standard: [ISO/IEC 19505-1:2012 & 19505-2:2012](https://www.iso.org/standard/52854.html) (Information technology — OMG Unified Modeling Language (OMG UML))
  - IEEE / Systems Architecture Standard: [ISO/IEC/IEEE 42010:2011](https://standards.ieee.org/ieee/42010/5387/) (Systems and software engineering — Architecture description)
  - Ecosystem support: Formal domain models, entity relationship diagrams, and interaction sequence diagrams across system architecture documentation.

- **Personal Health Devices & Health Informatics (Core Ecosystem Standard)**:
  - IEEE / ISO Standard: **[ISO/IEEE 11073 (PHDC)](https://standards.ieee.org/ieee/11073-20601/7133/)** (Health informatics — Personal health device communication standards suite, including IEEE 11073-20601 Optimized Exchange Protocol and device specializations)
  - US / EU Adoption: Harmonized by US FDA and European CEN/CENELEC for interoperable health sensor data exchange
  - Ecosystem support: Ingestion and synchronization of wearable biometric data (heart rate, sleep, steps, activity) in `CloudDash-Frontend-JavaAndroid` and processing in `CloudDash-Backend-ReactJS-API`.

## Additional links

- Product partners / homepage partners: https://www.healthdash.lv/partners
- SER (FAQ resopurce for CD/PCD users): https://www.healthdash.lv/SER
- Public Bug Tracker (Legacy, till Aug 20 2026): https://bitbucket.org/HolimaX/sandboxandroid/issues/new
- Public Bug Tracker: JIRA CLoud

---

(Committed: 2026-10-15) — Updated compliance, standards, and practices with formal EU, US, and IEEE standards references (including ISO/IEC/IEEE, IEEE 7002, IEEE 11073, EN 301 549, Section 508), and added WCAG 2.2 AA/AAA compliance line item across website and Admin Panel/Swagger.
