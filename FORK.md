# Fork Rationale

This repository is a stable, debranded reference pin of the [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel) project at commit `ca40aa72`, maintained by SHIVAM ITCS for the following reasons:

- **Pinned-source intake**: We consume the upstream as an immutable dependency (via source pin) to ensure reproducible builds and to avoid unexpected breakage from floating references.
- **Licence/attribution discipline**: All upstream copyrights and licenses are preserved (see NOTICE.md and LICENSE). We do not alter or remove upstream attribution.
- **Unmodified upstream baseline**: The source code in this fork is identical to the upstream at the pinned commit. No functional changes are made to the upstream codebase.
- **Branding without editing upstream**: Any rebranding (such as the SHIVAM ITCS name and contact information in the README) is confined to documentation and does not modify the upstream source.

## What this fork proves

This fork demonstrates SHIVAM ITCS's capability to:
- Maintain a clean, auditable fork of a critical upstream project.
- Preserve upstream provenance while integrating the project into our own ecosystem (e.g., .NET Core Azure AI Agentic Systems).
- Provide a stable reference for internal and external stakeholders regarding the exact version of the upstream we are using.

## What this fork is NOT

- **Not affiliated with Microsoft**: This fork is not endorsed, maintained, or affiliated with Microsoft or the upstream project's maintainers.
- **Not a redistribution product**: We do not redistribute this fork as a standalone product; it is used as a pinned dependency in our internal projects.
- **Not claiming upstream authorship**: We make no claim over the upstream authorship or the project's roadmap; we are merely consumers of the open-source release.