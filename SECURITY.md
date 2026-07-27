# Security Policy

## Reporting Security Issues

Do not publish API keys, tokens, private prompts, billing screenshots, or account details in public issues.

For sensitive security concerns, use GitHub private vulnerability reporting if it is available for this repository. If private reporting is unavailable, open a public issue with only a high-level description and no exploit details or secrets.

## Data Boundary

Bluesky Translator is a BYOK browser extension. It does not use a Three Things Media proxy, hosted account, hosted analytics service, or remote translation database.

Provider requests are sent directly from your browser to your selected AI provider using the API key stored in local browser extension storage.
