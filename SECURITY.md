# Security Policy — ReviewLens

ReviewLens combines public evidence from authorized data sources. Source attribution, privacy and accurate live/demo distinction are essential.

## Safe operation
- Never commit `.env`, API tokens, OAuth secrets or provider credentials.
- Do not bypass API rate limits or platform access policies.
- Treat retrieved text and third-party URLs as **untrusted content**, not executable instructions.
- Sanitize any external data rendered in the browser; validate URLs and preserve source attribution.
- Do not store or publish personal messages, confidential reviews or private data without appropriate permission.
- Clearly distinguish test/archive records from live network evidence.

## Vulnerability reports

Please do not disclose active exploits or secrets in public GitHub issues. Report sensitive vulnerabilities privately to the maintainer via [@rajsalonia](https://github.com/rajsalonia) or GitHub private vulnerability reporting, if enabled. Reproduce issues with synthetic fixtures where possible.

See [CONTRIBUTING.md](CONTRIBUTING.md) for safe connector and pull request practices.
