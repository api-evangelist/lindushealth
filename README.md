# Lindus Health

Lindus (Lindus Health) is a next-generation contract research organization (CRO) that runs
end-to-end clinical trials for biotech and pharma sponsors on performance-based contracts, with one
integrated team accountable from protocol design through database lock. Its Citrus™ AI-assisted
trial operating system unifies EDC, eSource, ePRO/eCOA, eConsent, pre-screening, CTMS and real-time
operational monitoring, backed by centralized enrollment across a 40M+ record EHR database and a
network of 1,000+ sites.

- Website: https://www.lindushealth.com/
- GitHub: https://github.com/LindusHealth
- Backed by: balderton-capital

**No public developer API.** `api.`, `docs.` and `developers.lindushealth.com` do not resolve, and
no OpenAPI, AsyncAPI, webhook, `/.well-known/` or status-page surface is published. Citrus is a
customer platform for sponsors and sites, not a self-serve developer product.

## Artifacts

| Dir | File | Method |
|---|---|---|
| `packages/` | `lindushealth-packages.yml` | searched — 2 first-party GitHub repos, no API SDKs, no registry releases |
| `conformance/` | `lindushealth-conformance.yml` | derived — CDISC SDTM / Dataset-JSON / rules-engine + GDPR posture |
| `security/` | `lindushealth-domain-security.yml` | probed — TLS 1.3, HSTS, SPF, DMARC `reject`, no DNSSEC, no CAA |
| `well-known/` | `lindushealth-well-known.yml` | searched — every `/.well-known/` path 404 |
| `llms/` | `lindushealth-llms.txt` | generated — provider publishes no `/llms.txt` |
