# Appendix 8: E-ITS Module Group to NIST CSF 2.0 and SP 800-53 Mapping

This appendix provides the complete module-group-level cross-framework mapping between E-ITS, NIST CSF 2.0 functions, and NIST SP 800-53 Rev. 5 control families. The mapping is based on dominant control intent at the module-group level, not on individual measure-level equivalence. For the complete measure-level NIST crosswalk, see Appendix 3.

Source population: Appendix 2 and Appendix 4, generated from the RIA E-ITS 2024 measures table. Accessed: May 1, 2026.

| E-ITS module group | E-ITS description | Primary CSF 2.0 function(s) | Secondary CSF 2.0 function(s) | Primary SP 800-53 families | Mapping rationale | E-ITS measures | Direct log-verifiable % |
|---|---|---|---|---|---|---|---|
| ISMS | Security Governance | Govern (GV) | — | PM, PL | Security governance, policy, risk management strategy, and oversight | 16 | 0.0% |
| ORP | Organisation and Personnel | Govern (GV) | Protect (PR) | PS, AT, PL | Organisational structure, personnel security, awareness and training | 55 | 7.3% |
| CON | Concepts and Methodologies | Protect (PR) | Identify (ID) | RA, SC, CP | Cryptography concepts, data protection, business continuity planning | 126 | 11.9% |
| OPS | Operations | Protect (PR) | Detect (DE) | CM, SI, MA | Operational procedures, patch and change management, outsourcing controls | 248 | 18.1% |
| DER | Detection and Response | Detect (DE) | Respond (RS) | AU, IR | Detection, logging, incident handling, forensics, and security event analysis | 111 | 10.8% |
| INF | Infrastructure | Protect (PR) | — | PE | Physical infrastructure, buildings, data centers, server rooms, cabling | 214 | 6.1% |
| NET | Networks and Communication | Protect (PR) | Detect (DE) | SC, AC | Network architecture, segmentation, firewalls, VPN, wireless security | 213 | 10.8% |
| SYS | IT Systems | Protect (PR) | Identify (ID) | AC, CM, IA | Servers, clients, mobile devices, virtualization, containerization | 459 | 12.2% |
| APP | Applications | Protect (PR) | Govern (GV) | SA, SI, AC | Applications, web services, databases, directory services, AI systems | 291 | 10.0% |
| IND | Industrial IT | Protect (PR) | Identify (ID) | SI, PE, SC | Industrial control systems, OT environments, process control networks | 69 | 17.4% |
| SYS.EE | Estonian IT Systems | Protect (PR) | Detect (DE) | IA, AC, AU | X-tee data exchange infrastructure and eID components; included in SYS totals | (in SYS) | — |
| APP.EE | Estonian Applications | Protect (PR) | Govern (GV) | SA, SI, PM | Estonian-specific applications, X-tee data services, and AI systems; included in APP totals | (in APP) | — |

Cross-framework observations:

1. DER maps most strongly to Detect/Respond and AU/IR, because detection, logging, incident handling, and forensic activities are evidence-oriented.
2. ISMS maps to Govern and programme/planning families, which explains its absence of direct log-verifiable measures.
3. Protect remains the dominant CSF function across E-ITS module groups, but direct log-verifiability still varies by module because not all Protect controls create observable events.
4. Recover (RC) is not used as the primary module-level function because recovery-oriented measures are distributed across CON, OPS, DER, and selected technical modules rather than concentrated in a single E-ITS top-level module. Recovery-related individual measures are mapped at measure level in Appendix 3.
5. SYS.EE and APP.EE are included in SYS and APP totals respectively; they are shown separately only to highlight Estonian-specific scope.

Abbreviations:

| Code | SP 800-53 family |
|---|---|
| AC | Access Control |
| AT | Awareness and Training |
| AU | Audit and Accountability |
| CA | Assessment, Authorization, and Monitoring |
| CM | Configuration Management |
| CP | Contingency Planning |
| IA | Identification and Authentication |
| IR | Incident Response |
| MA | Maintenance |
| MP | Media Protection |
| PE | Physical and Environmental Protection |
| PL | Planning |
| PM | Program Management |
| PS | Personnel Security |
| PT | PII Processing and Transparency |
| RA | Risk Assessment |
| SA | System and Services Acquisition |
| SC | System and Communications Protection |
| SI | System and Information Integrity |
| SR | Supply Chain Risk Management |

Sources:

- NIST, *The NIST Cybersecurity Framework (CSF) 2.0*, https://doi.org/10.6028/NIST.CSWP.29. Accessed: May 11, 2026.
- NIST, *Security and Privacy Controls for Information Systems and Organizations*, NIST SP 800-53 Rev. 5, https://doi.org/10.6028/NIST.SP.800-53r5. Accessed: May 11, 2026.
- RIA, *Estonian Information Security Standard (E-ITS)*, https://www.ria.ee/en/cyber-security/management-state-information-security-measures. Accessed: May 11, 2026.
