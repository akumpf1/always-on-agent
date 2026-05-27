## Compliance Scan: compliance-acme
**Contract:** acme-data-platform.md (Acme Data Platform Ltd.)
**Scanned:** 2026-05-27
**Violations Found:** 4

## Violations

### 1. 🔴 Data Residency
- **Policy:** EU customer data must remain in EU. No US/APAC processing permitted.
- **Contract (§2):** "Vendor may process customer data in any region...including the United States, Ireland, and Singapore. Vendor will use reasonable efforts to keep EU data within EU regions but does not guarantee residency."
- **Fix:** Replace §2 with: "Vendor shall process EU customer data exclusively within the EU/EEA. Processing in US or APAC regions is not permitted without prior written consent."

### 2. 🔴 Subprocessors
- **Policy:** 30 days advance written notice before adding a new subprocessor.
- **Contract (§6):** "Vendor will update the list within 30 days of any change." — retrospective, not advance notice.
- **Fix:** Replace §6 with: "Vendor will provide at least 30 days' written notice before engaging any new subprocessor."

### 3. 🟡 Data Breach Notification
- **Policy:** Vendor must notify within 72 hours of detecting a breach.
- **Contract (§7):** "Vendor will notify the customer within 96 hours of confirming a security incident."
- **Fix:** Change §7 to: "Vendor will notify the customer within 72 hours of detecting a security incident affecting the customer's data."

### 4. 🟡 Governing Law
- **Policy:** Must be England & Wales, Ireland, US Delaware, or equivalent.
- **Contract (§8):** "Governed by the laws of the State of California, United States."
- **Fix:** Change §8 to: "This Agreement is governed by the laws of England and Wales."

## Proposed Remediation
Open renegotiation request with Acme Data Platform Ltd. on all four clauses. Priority: Data Residency and Subprocessors (immediate risk). Breach notification and Governing Law at next renewal.
