# Security policy

SafeStack partners is a curated documentation repository. It does not execute the external tools listed here and it does not store credentials, private keys or production data.

## Reporting a vulnerability

Please do not open a public issue for a suspected secret, credential, private key, exploitable workflow or other sensitive security problem.

Use GitHub's **Report a vulnerability** button on the repository Security tab when private vulnerability reporting is available. If that option is unavailable, contact the SafeStack maintainers through the organization profile and include only the minimum reproducible details needed to validate the report.

Please include:

- the affected file, URL or workflow;
- a clear impact statement;
- safe reproduction steps that do not access data you do not own;
- a proposed remediation, if known.

Never include live credentials, private keys, access tokens or personal data in an issue, pull request or report. Revoke any credential that was accidentally exposed before reporting it.

## Scope

Reports about third-party services listed in the catalogue must be sent to that service through its own published security or bug-bounty process. SafeStack can correct the catalogue entry, but it cannot accept responsibility for an external service.

## Verification

Changes to project identity should be checked against the separately signed [SafeStack public key registry](https://github.com/kibernetinio-saugumo-sprendimai/safestack-project-public-keys). Public documentation never replaces local verification and independent review.
