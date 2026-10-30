# Orbital credential assurance

The source register and control-event export are retained as sealed assessment evidence.

<!-- CREDENTIAL-CUSTODY:BEGIN -->
## Credential custody — 15 December 2026
Credentials: 7 | Current: 1 | Due soon: 2 | Overdue: 2 | No rotation: 1 | Exempt: 1
Actions required: 5

| Credential | Owner | System | Tier | Last rotation | Due | Exemption through | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| CR-API | Ava | payments-api | CRITICAL | 2026-11-25 | 2026-12-25 | NONE | DUE_SOON |
| CR-BKP | Bo | backup-vault | STANDARD | 2026-08-01 | 2026-10-30 | NONE | OVERDUE |
| CR-CI | Ava | build-runner | STANDARD | NONE | NONE | NONE | NO_ROTATION |
| CR-DNS | Cy | dns-control | CRITICAL | 2026-11-01 | 2026-12-16 | NONE | DUE_SOON |
| CR-ERP | Bo | finance-erp | CRITICAL | 2026-12-01 | 2026-12-31 | 2027-01-15 | EXEMPT |
| CR-LOG | Cy | log-archive | STANDARD | 2026-10-01 | 2027-01-29 | NONE | CURRENT |
| CR-VPN | Di | remote-access | CRITICAL | 2026-11-15 | 2026-12-15 | NONE | OVERDUE |
<!-- CREDENTIAL-CUSTODY:END -->

Questions about system ownership belong with Security Operations.
