# ARYN — Controlled Documentation

Private documentation repository for ARYN. This scaffold **does not include the nine completed corporate documents**. Upload the approved versions, maintaining document IDs and version metadata.

Directory responsibilities:
- `corporate/`: ARYN-CORP-001, ARYN-BUS-001, market and financial documents.
- `product/`: ARYN-PRD-001 and product acceptance.
- `architecture/`: ARYN-ARCH-001, ARYN-TECH-001 and ADRs.
- `security/`: ARYN-SEC-001 and controlled risk assessments.
- `engineering/`: API schema, test and implementation notes.
- `operations/`: runbooks, releases, deployment and ARYN-PLAN-001.

Do not upload customer data, credentials, API tokens or signing keys. Mark draft documents clearly and retain historical versions.

Source-derived application contracts and retained runtime verification are indexed
in [engineering/aryn](engineering/aryn/README.md), with source commit/blob and copy
hashes. Their import does not approve or replace any of the nine normative
documents in [the controlled index](DOCUMENT_INDEX.md). Owner-approved publication
targets `main` and precedes the corresponding deletions from application source.
