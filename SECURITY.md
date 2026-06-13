# Health Sync Security

## Security Pledge

Health Sync handles user-authorized Apple Health records and is designed around local-first, privacy-preserving behavior. The app exports data to the user's own iCloud Drive location and does not operate a developer-controlled ingestion server for those files.

We will treat credible reports about data exposure, unsafe export behavior, account handling, or document leakage as high priority.

## Reporting Vulnerabilities

Use public issues only for non-sensitive reports:

https://github.com/GoBeromsu/health-sync-support/issues

If a report requires sensitive details, open a minimal public issue asking for a private contact path first. Do not post personal records, account credentials, payment details, screenshots containing personal records, or files produced by the app in public issues.

## Scope

In scope:

- Public support repository documents.
- Health Sync app behavior that could expose user-authorized records outside the user's intended iCloud Drive export path.
- Subscription or purchase flows that could expose sensitive account or payment state in app logs or public reports.

Out of scope:

- Reports that require access to another user's device, iCloud account, or records.
- Social engineering or physical access attacks.
- Automated high-volume testing against Apple services or GitHub.
