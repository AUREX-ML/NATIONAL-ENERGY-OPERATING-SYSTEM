# Security Policy

## Scope

This repository currently contains programme documentation and architecture. It does not currently contain production software, credentials, operational access, or live infrastructure configuration.

Security remains central because the proposed programme concerns energy-sector digital infrastructure and may later involve monitoring, coordination, or control of physical energy assets.

## Reporting Security Concerns

Do not publish sensitive security findings in public issues.

For now, report security concerns directly to the repository owner through the GitHub project owner channel. If a formal security contact is established later, this file should be updated with the approved contact method.

## Sensitive Information

Do not commit:

- credentials, tokens, keys, certificates, or passwords;
- live infrastructure details;
- private network diagrams;
- facility-specific security weaknesses;
- exploitable vulnerability details;
- personal data;
- confidential customer, utility, government, or partner information.

## Security Principles

Future implementation work should follow:

- least privilege;
- explicit identity and authorization;
- secure credential lifecycle;
- command auditability;
- local safety supremacy;
- secure update and rollback;
- network segmentation;
- logging and monitoring;
- incident response;
- vulnerability management;
- supply-chain review.

## Control Authority

Any future remote monitoring or control capability must be authorized, bounded, logged, reviewable, and subordinate to local physical safety and applicable law, regulation, grid code, contract, and consent.

