
# DOPPEL — Your Data. Your Intelligence.

A local-first personal attack-path intelligence and privacy-defense concept created for **wHACKiest 2026** (Track: *Know Thyself — Your Data. Your Intelligence.*)

## Overview
People routinely share scattered fragments of personal data—public bios, social tags, activity logs, and contact details—without seeing how attackers chain those pieces together into impersonation, social engineering, or financial fraud. **DOPPEL** focuses on mapping those connections into an explainable attack-path graph and identifying lowest-friction edits using Cost-Weighted Minimum Cut to reduce exposure.

## Team & Event Details
* **Event:** wHACKiest 2026 
* **Team Name:** Novacane
* **Team ID:** `f3d8eb27`
* **Colleges:** BIT & BMSIT
* **Members:**
  * **Keshav Jha** (Lead) — USN: `1BY25CB023`
  * **Aadya Singh** — USN: `1BI25AI002`

## Planned Stack & Integrations
* **Frontend & Extension:** Streamlit, PyVis/Plotly, Manifest V3 browser extension, Web Crypto (`AES-256-GCM`)
* **Backend & Graph:** Python 3.11, NetworkX, Pydantic, `gpxpy`
* **Local AI / Parsing:** `spaCy`, Regex, Chrome Built-in AI (Gemini Nano), Ollama
* **APIs & Cloud:** ElevenLabs API (labelled voice awareness drills), AWS S3 (encrypted backup storage)
* **Isolation & Integrity:** Docker (`--network none`), local SQLite / ephemeral JSON, `hashlib` (SHA-256 session-wipe receipts)
