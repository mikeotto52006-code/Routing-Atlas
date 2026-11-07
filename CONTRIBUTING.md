# Contributing to Routing Atlas

Routing Atlas publishes structured, source-backed research. Contributions that improve accuracy, coverage, or traceability are welcome.

## Before submitting

1. Search the [findings index](FINDINGS-INDEX.md) and [dataset](data/findings.json) to check whether the subject is already covered.
2. Consult primary sources such as official documentation, specifications, project repositories, release notes, or original research.
3. Identify the relevant version, publication date, commit, or specification section wherever possible.

## Evidence requirements

A proposed finding should contain:

| Field | Purpose |
| --- | --- |
| ID | Stable identifier for the claim |
| Title | Concise description |
| Finding | Specific, verifiable statement |
| Source URL | Public primary-source reference |
| Source details | Version, section, release, commit, or date |
| Open question | Any important uncertainty or untested behavior |
| Research area | Topic or system being investigated |
| Inspection date | Date the source was reviewed |

Differentiate vendor claims, independently demonstrated behavior, and unverified hypotheses. Do not present a demonstration as proof of broader compatibility. Update outdated findings with references to the changed documentation.

## Publishing standards

Only publish information appropriate for a public repository. Do not include credentials, personal data, private infrastructure configurations, proprietary material, access tokens, or non-public logs. Avoid publishing third-party content beyond what is necessary for citation and analysis.

## Review and updates

Open an issue to discuss a proposed finding, or submit a pull request with a structured change. Existing claim identifiers should remain stable when correcting a finding.

The repository is a published research dataset. Contributions here do not automatically update the originating research workspace; reconciliation must be handled separately.

Accuracy, traceability, and explicit uncertainty take priority over volume.
