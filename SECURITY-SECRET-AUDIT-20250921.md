# Secret Audit — motionmavericks/all-in-one — 20250921

- generated: 2025-09-21T16:01:17+10:00
- gitleaks: 8.18.4
- trufflehog: not_run
- deep_scan: true

## Findings (redacted)

- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: 
  - Excerpt: secret = REDACTED

- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: dd52074adb75d8022a64eafe089fb03ff3ae9c35
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: 3c729d0746f338672208be0f2a2f433f2a237602
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: e5d7b7cd7e636a88c67b2bb52882a773d60e1a63
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: a9de130a2ccba3dbaa93b2271d539ce46071d2e4
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: 3957a03b2d5ff87e268e994f85c2a9fb2457108a
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: e0916df031bc6d23412ac799830682f73febc9c3
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: 5c30a6472f2c4b59b14c0266490f25f17cc2e27c
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: fe561976e9b70034bd445badeb95202e46a0f711
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: 81fec27c1499c9d93cec173d86e361d5d63cf260
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: 0fe4ea3238f1d4475992014bf730d8d630eebfdb
  - Excerpt: secret = REDACTED
- Detector: generic-api-key
  - Location: Containers/talk/server.conf.in:228
  - Commit: 68ae9c055a4cd99e319f19dd2ac42e4cbc85134b
  - Excerpt: secret = REDACTED

## Remediation plan
- Replace hard-coded secrets with env vars or secret manager references.
- Add .gitignore for .env*, credentials, and build artifacts.
- Add pre-commit hook to run `gitleaks protect`.
- Rotate any exposed keys at the provider.

## History rewrite (optional)
- Only performed if CONFIRM_HISTORY_REWRITE=true.
- Force-push required. May break forks and SHAs.
