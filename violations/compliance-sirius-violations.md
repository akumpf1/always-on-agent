## Compliance Scan: compliance-sirius
**Contract:** sirius-storage.md (Sirius Storage SDN BHD)
**Scanned:** 2026-05-27
**Violations Found:** 7 — CRITICAL: This contract fails every policy requirement.

## Violations

### 1. 🔴 Data Residency
- **Policy:** EU data must remain in EU.
- **Contract (§2):** Data stored in Malaysia and Singapore. No EU residency provisions. Sirius may relocate data at sole discretion.
- **Fix:** Require EU-region data centres for EU customer data, or exclude EU data from this vendor entirely.

### 2. 🔴 Audit Rights
- **Policy:** Audit on no more than 90 days' notice.
- **Contract (§3):** 180 days' notice required, max once every 2 years.
- **Fix:** Require audit rights on 30 days' notice, at least annually.

### 3. 🔴 Termination for Convenience
- **Policy:** Must be able to terminate with ≤90 days' notice.
- **Contract (§4):** "Termination for convenience is not permitted during the initial term." Initial term is 5 years.
- **Fix:** Add termination for convenience clause with 90 days' notice effective immediately.

### 4. 🔴 Liability Cap
- **Policy:** Minimum 12 months of fees paid.
- **Contract (§5):** Capped at 3 months of fees, including for data breach.
- **Fix:** Increase cap to 12 months minimum; carve out data breach from cap.

### 5. 🔴 Subprocessors
- **Policy:** 30 days advance written notice.
- **Contract (§6):** "Sirius may engage any subprocessor it deems appropriate without prior notice."
- **Fix:** Require 30 days advance written notice for any new subprocessor.

### 6. 🔴 Data Breach Notification
- **Policy:** Within 72 hours of detection.
- **Contract (§7):** "In due course, taking into account the nature and circumstances." No defined window.
- **Fix:** Replace with: "Sirius will notify customer within 72 hours of detecting a confirmed breach."

### 7. 🔴 Governing Law
- **Policy:** England & Wales, Ireland, or US Delaware.
- **Contract (§8):** Malaysia — no recognised data protection regime.
- **Fix:** Change to England & Wales or Ireland.

## Recommended Action
⚠️ DO NOT RENEW this contract without full renegotiation. Consider terminating early if feasible given §4 restrictions. Escalate to legal immediately.
