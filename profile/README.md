# Healthdash GitHub Organization profile

This repository contains organization-level information and links to the HealthDash ecosystem. This file is the GitHub org profile README (displayed from `.github/profile/README.md`).

Updated: 2026-09-07

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

- android-oauth-client
  - Produces: Android library artifacts (AAR/JAR) and source releases.
  - Distributed: Maven Central (where applicable) and GitHub Releases.
  - Tokenless repo badges (example):
    - [![Release](https://img.shields.io/github/v/release/Healthdash/android-oauth-client?label=release)](https://github.com/Healthdash/android-oauth-client/releases)
    - [![Last commit](https://img.shields.io/github/last-commit/Healthdash/android-oauth-client)](https://github.com/Healthdash/android-oauth-client/commits)
    - [![Open issues](https://img.shields.io/github/issues/Healthdash/android-oauth-client)](https://github.com/Healthdash/android-oauth-client/issues)

- PizzaDelivery
  - Produces: example Android app and sample source used for demos and testing.

- demo-repository
  - Produces: demo content and onboarding materials.

- .github
  - Produces: organization-level configuration and this profile README.

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

- camelCase: https://en.wikipedia.org/wiki/Camel_case
- SPDX license list: https://spdx.github.io/license-list-data
- Semantic Versioning: https://semver.org/
- OpenGraph: https://www.opengraph.io/documentation
- AMP: https://www.amp.dev
- SPA (React glossary): https://reactjs.org/docs/glossary.html
- PWA: https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps
- Security certifications guidance: https://ubuntu.com/security/certifications/docs
- Privacy regulations: CCPA https://www.oag.ca.gov/privacy/ccpa, GDPR https://gdpr.eu/what-is-gdpr/
- UML 2.5: https://www.uml-diagrams.org/uml-25-diagrams.html

## Additional links

- Product partners / homepage partners: https://www.healthdash.lv/partners
- SER: https://www.healthdash.lv/SER

---

(Committed: 2026-09-07) — Restored distribution & communication links, described produced artifacts per repo (CloudDash first), reintroduced tokenless repo-level badges, and added maintainers/access instructions.
