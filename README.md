> [!CAUTION]
> This repository is a workspace copy for navigation, drafting, version control and collaboration. It is not the official statement of government policy and must not be relied on as such. For the official published policy, see the [UK digital verification services trust framework 1.0 pre-release on GOV.UK](https://www.gov.uk/government/publications/uk-digital-verification-services-trust-framework-1-0/uk-digital-verification-services-trust-framework-1-0-pre-release).

![Office for Digital Identities and Attributes](media/ofdia-banner.png)

# UK digital verification services trust framework

A Markdown-first, version-controlled workspace for the **UK digital verification services (DVS) trust framework**, maintained on behalf of the [Office for Digital Identities and Attributes (OfDIA)](https://www.gov.uk/government/organisations/office-for-digital-identities-and-attributes).

The authoritative publication lives on GOV.UK:

- [UK digital verification services trust framework 1.0 (pre-release)](https://www.gov.uk/government/publications/uk-digital-verification-services-trust-framework-1-0/uk-digital-verification-services-trust-framework-1-0-pre-release)

This repository mirrors that publication as a set of Markdown files so the framework is easier to navigate, review, cite, discuss and propose changes to. Changes made here do not, by themselves, change government policy.

> [!IMPORTANT]
> The 1.0 publication is currently in **pre-release**. It has been published in this form to give providers certainty about the forthcoming rules and time to prepare, but services **cannot yet be certified against it** and it **does not yet have legal effect**. Final publication will follow once the relevant accreditation work is complete.

## Trust Framework 1.0

The 1.0 publication is split into one Markdown file per main numbered section, organised into the four published Parts. The [Trust Framework 1.0 landing page](trust-framework-1.0/README.md) is the single starting point for this version.

- [0. Version and certification validity notes](trust-framework-1.0/00-version-and-certification-validity-notes.md)

**[Part 1 — Background and context](trust-framework-1.0/part-1/README.md)**

- [1. Introduction](trust-framework-1.0/part-1/01-introduction.md)
- [2. Feedback received and updates](trust-framework-1.0/part-1/02-feedback-received-and-updates.md)
- [3. Terms and definitions](trust-framework-1.0/part-1/03-terms-and-definitions.md)
- [4. How organisations participate in the trust framework](trust-framework-1.0/part-1/04-how-organisations-participate-in-the-trust-framework.md)

**[Part 2 — Rules for providers by role](trust-framework-1.0/part-2/README.md)**

- [5. Rules for identity service providers](trust-framework-1.0/part-2/05-rules-for-identity-service-providers.md)
- [6. Rules for attribute service providers](trust-framework-1.0/part-2/06-rules-for-attribute-service-providers.md)
- [7. Rules for holder service providers](trust-framework-1.0/part-2/07-rules-for-holder-service-providers.md)
- [8. Rules for orchestration service providers](trust-framework-1.0/part-2/08-rules-for-orchestration-service-providers.md)
- [9. Rules for component service providers](trust-framework-1.0/part-2/09-rules-for-component-service-providers.md)

**[Part 3 — Rules for all service providers](trust-framework-1.0/part-3/README.md)**

- [10. Inclusivity, accessibility and service design](trust-framework-1.0/part-3/10-inclusivity-accessibility-and-service-design.md)
- [11. Operational requirements](trust-framework-1.0/part-3/11-operational-requirements.md)
- [12. Service requirements](trust-framework-1.0/part-3/12-service-requirements.md)
- [13. The register of digital identity and attribute services](trust-framework-1.0/part-3/13-the-register-of-digital-identity-and-attribute-services.md)
- [14. The UK CertifID trust mark](trust-framework-1.0/part-3/14-the-uk-certifid-trust-mark.md)

**[Part 4 — Additional information](trust-framework-1.0/part-4/README.md)**

- [15. Table of standards, guidance and legislation](trust-framework-1.0/part-4/15-table-of-standards-guidance-and-legislation.md)
- [16. Glossary of terms and definitions](trust-framework-1.0/part-4/16-glossary-of-terms-and-definitions.md)

## Other folders

| Folder | What it contains |
| --- | --- |
| [`media/`](media/README.md) | Figures referenced by the publication, plus reserved filenames for future top-level banner images. |
| [`supporting-material/`](supporting-material/README.md) | Derived artefacts (such as a machine-readable mirror of the glossary) and helper scripts. Not part of the official publication. |
| [`supplementary-codes/`](supplementary-codes/README.md) | Stub folder reserved for future supplementary codes (right to work, right to rent, Disclosure and Barring Service identity checks) in the same format. |
| [`trust-framework-1.0/additional-information/`](trust-framework-1.0/additional-information/README.md) | Stub for editorial material sitting alongside 1.0 but not part of the published text. |

## Contributing

This repository exists in part to make feedback on the trust framework — from providers, regulators, researchers, assistive-technology users, policy specialists, plain-English reviewers and the wider public — easier and more structured to gather.

- [`CONTRIBUTING.md`](CONTRIBUTING.md) — how to raise issues, open pull requests and start discussions.
- [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) — templates for typo, clarity, structural, accessibility, broken-link, policy-feedback and supporting-material contributions.
- [`KNOWN-ISSUES.md`](KNOWN-ISSUES.md) — items already identified by maintainers.
- [`SECURITY.md`](SECURITY.md) — how to report a security issue (don't raise one as a public GitHub issue).

## Repository design and versioning

- [`ARCHITECTURE.md`](ARCHITECTURE.md) — design decisions behind the repository layout, and how it relates to the GOV.UK publication.
- [`VERSIONS.md`](VERSIONS.md) — how multiple publication versions sit side by side in this repository over time.
- [`CHANGELOG.md`](CHANGELOG.md) — notable changes to the repository and to the publication text, tracked separately.
- [`docs-site/`](docs-site/README.md) — Eleventy-based GOV.UK-styled rendered view of the repository, deployed to GitHub Pages. Not authoritative; the authoritative publication stays on GOV.UK.

## Licence

Following the [GDS Way licensing manual](https://gds-way.digital.cabinet-office.gov.uk/manuals/licensing.html), this repository is dual-licensed: documentation under the Open Government Licence v3.0, code under the MIT License. See [`LICENCE.md`](LICENCE.md).

## Related reading

- [Office for Digital Identities and Attributes (OfDIA)](https://www.gov.uk/government/organisations/office-for-digital-identities-and-attributes) on GOV.UK
- [OfDIA blog](https://enablingdigitalidentity.blog.gov.uk/) — ongoing commentary and updates from the team
