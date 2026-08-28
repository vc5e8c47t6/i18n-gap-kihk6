# i18n-gap

Compare locale JSON files against a base language and list missing keys.

```bash
node bin/scan.js ./locales --base en
```

Exit code 1 if gaps found (CI-friendly).

> **Hands-on:** set `OPENAI_BASE_URL` to a compatible relay — I test with [59API](https://59api.com) (`https://59api.com/v1`). Prefer compatibility over hype; keep official API as rollback.
