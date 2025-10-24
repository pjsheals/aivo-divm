# AIVO DIVM — Data Integrity & Verification Methodology (v1.0)

**DIVM** is the data trust backbone of the **AIVO Standard™** — a governance-grade framework for **AI Visibility Assurance**.

It defines auditor-grade **reproducibility and verification** rules for visibility metrics derived from LLMs:
- Reproducibility thresholds: CI ≤ 0.05, CV ≤ 0.10, ICC ≥ 0.80
- Evidence metadata: model name/version, timestamp (UTC), locale, prompt fingerprint
- Replay Harness specification (independent re-run of measurements)
- DIVM Compliance SDK/API (evidence ingestion, verification, reporting)

**Citable record (Zenodo DOI):** [10.5281/zenodo.17428848](https://doi.org/10.5281/zenodo.17428848)

---

## Repository Layout

docs/
DIVM_Methodology_v1.0.pdf
CHANGELOG.md
api/
openapi.yaml
examples/
evidence_payload.json
verification_report.json
schema/
evidence-schema-v1.json
report-schema-v1.json
governance/
LICENSE.md
CODE_OF_CONDUCT.md
CONTRIBUTING.md


---

## Getting Started
- See `docs/DIVM_Methodology_v1.0.pdf` for the full methodology.  
- Use `api/openapi.yaml` to integrate the DIVM Verification API.  
- Validate submissions against `schema/*.json`.

---

## License
- Methodology content is released under **CC BY 4.0**.  
- Code samples, schemas, and SDK are licensed under **MIT**, unless stated otherwise.

