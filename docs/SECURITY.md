# Security and privacy floor
No accounts, checkout, backend, secrets or external data collection. Public deployment intentionally serves educational fictional scenarios. No payment promise or automatic system action.

- Strict numeric allowlist with bounds and finite checks; validate again on loading local data. Fixed scenario identifiers only; no text input or customer identity stored. Five-scenario/40 KB cap. HTML output contains validated numbers; saved rows use textContent.
- LocalStorage is opt-in, unencrypted and visible to other device users. Load/delete/all-delete controls. Errors for disabled, full or corrupted storage. Numeric scenario data is not backup or restore evidence.
- Planner values/event log remain in memory. Exported plan files may include scenario data; use fictional approximations. Reset clears that session, not simulator storage; simulator deletion is on /pricing.
- CSP, nosniff, no-referrer, DENY frames, disabled camera/microphone/geolocation, no form submission. HTTPS/HSTS supplied by Vercel and verified on first release.
- Optional Week 8 WebLLM retained, opt-in on /plan, separate lazy-loaded assets; model downloads contact Hugging Face/GitHub and consume bandwidth/memory. It cannot choose prices, operate accounts or attest to protection. No new AI calls required by pricing.
- Sources reviewed for unexpected transmission and old prices. 29 automated regression/math/storage/header checks expected after final run; actual report governs.
- Dependencies pinned in existing lockfile, reused from Week 13. No current registry vulnerability audit completed: local network unavailable. Do not claim vulnerability-free. Large optional AI bundles persist as a documented inherited limitation.
- Real research stays private with anonymized public summaries. Never publish credentials, e.firma, real backup content, customer files, addresses or unconsented recordings. The shadow clause forbids monetizing vulnerability, fear-based conversion or false assurance.
