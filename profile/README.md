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
  - Produces: static web application build (HTML, JS, CSS, assets) packaged by the frontend build pipeline.
  - Distributed: served from clouddashboard.healthdash.com and deployed to the production hosting environment (see repo README for deployment details).

- CloudDash-Backend-ReactJS-API
  - Produces: backend service releases (Node.js artifacts) and Docker images used by staging/production.
  - Distributed: Docker images and GitHub Releases; used by the PCD deployment pipeline.

- CloudDash-Frontend-JavaAndroid
  - Produces: Android application packages (APK / AAB) and release builds.
  - Distributed: Google Play Store (public/private tracks); CI produces signed artifacts for release.

- CloudDash-Frontend-GoLangComponents
  - Produces: Go-based CLI tools and static binaries used in CI and admin tooling.
  - Distributed: release binaries attached to GitHub Releases and internal tooling registries.

- CloudDash-Frontend-PythonComponents
  - Produces: Python/Flask microservice packages and Docker images for optional extension services (PCD apps).
  - Distributed: Docker images, PyPI/internal package registry (when applicable), and GitHub Releases.

- android-oauth-client
  - Produces: Android library artifacts (AAR/JAR) and source releases.
  - Distributed: Maven/Central or GitHub Releases where applicable.

- PizzaDelivery
  - Produces: example Android app and sample source used for demos and testing.
  - Distributed: sample artifacts via Releases.

- demo-repository
  - Produces: demo content and onboarding materials.

- .github
  - Produces: organization-level configuration and this profile README.

Note: exact artifact formats and distribution targets are maintained in each repository's README. If you need a specific artifact location (for CI, S3 bucket paths, Docker registry, or Play Store links) tell me which repo and I can add the exact URLs and access instructions.

## Communication & Collaboration channels (restored)

- Google Groups (customers / collaborators): https://groups.google.com/g/huaweihealthsyncv1y2022
- StackOverflow Teams (developer collaboration): https://stackoverflow.com/c/healthdash
- Keybase (development documentation & team): keybase://team/healthdash
- Wordpress (product blog / updates): https://linardsliepins.wordpress.com/
- Bitbucket (public bug tracker / legacy issues): https://bitbucket.org/HolimaX/sandboxandroid/issues/new

These channels are used for different audiences (customers, developers, testers). For private/professional support use organization-managed channels and request access if needed.

## CI / Build badges

CI badges with embedded tokens were removed from the org profile to avoid exposing secrets. Reintroducing badges should use tokenless badge URLs or repository-level badges in each repo's README. If you want me to restore badges for specific repos, I will add them per-repo using safe badge URLs.

## Support & Where to get help

- For bugs or feature requests: open an issue in the repository that best matches the component (example: https://github.com/Healthdash/CloudDash-Backend-ReactJS-API/issues).
- For access requests or cross-repo coordination: open an issue in this repository (https://github.com/Healthdash/.github/issues) or contact a maintainer (see list below).
- For urgent production incidents: notify the on-call maintainer or the organization owners.

## Maintainers & Access Instructions (updated)

- Primary maintainer / contact: @HolimaX (Linards) — active committer and organization owner.
- Organization owners and maintainers: see the Healthdash organization members and teams (https://github.com/Healthdash). If you need a specific point of contact for a repo, open an issue or mention @HolimaX and a repository owner will respond.

How to request access or become a contributor:
- 1) Open an issue in the relevant repository explaining why you need access and which resources (CI, Docker registry, Play Store, backend credentials) you need.
- 2) Provide your GitHub username and the minimum required access level.
- 3) A repository owner or org admin will respond and either invite you to the organization/team or provide alternative access.

If you are an organization admin and want to add a maintainer entry here with an email or additional GitHub handles, tell me which details to include and I will update the profile.

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

(Committed: 2026-09-07) — Restored distribution & communication links, described produced artifacts per repo, and added maintainers/access instructions. If you want me to include exact artifact locations (S3, Docker registry, Play Store release URLs), provide the target repo(s) and I'll add them to the appropriate repository READMEs or this profile.