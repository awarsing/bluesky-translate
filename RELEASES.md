# Release Notes

## 0.1.0

Updated Chrome release package.

Chrome package:

- File: bskytranslate-publicextension-0.1.0-chrome.zip
- Size: 901,617 bytes
- SHA-256: 7385fdc7392ca303a8d3754bf206bd203d00e4f973c0e7bbb26be3f0afa6fe6b

Changes in this package:

- Fixes completed translations not rendering until page refresh on Bluesky timelines.
- Adds focused cache, metrics, DOM, and controller regression coverage.
- Cleans up duplicated metrics, validation, pattern, hash, and provider request logic.
- Adds non-strict Knip and Fallow inventory tooling for source hygiene.

Initial extension capabilities:

- Inline English translation cards for Bluesky posts.
- Local language filtering before provider requests.
- Bring-your-own-key provider setup.
- Groq, OpenAI, Google Gemini, and Anthropic provider support.
- Local translation cache with cache clearing from Settings.
- Local usage dashboard for posts, cache hits, requests, and token totals.
- Normal tab Settings page for provider setup and diagnostics.
- Privacy policy and support documentation.