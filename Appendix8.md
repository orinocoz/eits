Appendix 8: E-ITS Module Group to NIST CSF 2.0 and SP 800-53 Mapping

This appendix accompanies Table 6 in the thesis and provides the complete module-group-level cross-framework mapping between E-ITS, NIST CSF 2.0 functions, and NIST SP 800-53 Rev. 5 control families. The mapping is based on dominant control intent at the module-group level, not on individual measure-level equivalence. For measure-level NIST crosswalk, see Appendix B.

| E-ITS module group | E-ITS description | Primary CSF 2.0 function(s) | Secondary CSF 2.0 function(s) | Primary SP 800-53 families | Mapping rationale | E-ITS measures | Direct log-verifiable % |
|---|---|---|---|---|---|---|---|
| ISMS | Security Governance | Govern (GV) | — | PM, PL | Security governance, policy, risk management strategy, and oversight | 16 | 0.0% |
| ORP | Organisation and Personnel | Govern (GV) | Protect (PR) | PS, AT, PL | Organizational structure, personnel security, awareness and training | 55 | 10.9% |
| CON | Concepts and Methodologies | Identify (ID) | Protect (PR) | RA, SC, CP | Cryptography concepts, data protection, business continuity planning | 126 | 11.9% |
| OPS | Operations | Protect (PR) | Detect (DE) | CM, SI, MA | Operational procedures, patch and change management, outsourcing controls | 248 | 16.9% |
| DER | Detection and Reaction | Detect (DE) | Respond (RS) | AU, IR | Detection, logging, incident handling, forensics, and security event analysis | 111 | 36.0% |
| INF | Infrastructure | Protect (PR) | — | PE | Physical infrastructure, buildings, data centers, server rooms, cabling | 214 | 4.2% |
| NET | Networks and Communication | Protect (PR) | Detect (DE) | SC, AC | Network architecture, segmentation, firewalls, VPN, wireless security | 213 | 14.1% |
| SYS | IT Systems | Protect (PR) | Identify (ID) | AC, CM, IA | Servers, clients, mobile devices, virtualization, containerization | 459 | 13.5% |
| APP | Applications | Protect (PR) | — | AC, SI | Applications, web services, databases, directory services, email systems | 291 | 12.0% |
| IND | Industrial IT | Protect (PR) | Identify (ID) | SI, PE | Industrial control systems, OT environments, process control networks | 69 | 14.5% |
| SYS.EE | Estonian IT Systems | Protect (PR) | — | IA, AC | X-tee data exchange infrastructure, eID components (Estonia-specific, no BSI counterpart) | (in SYS) | — |
| APP.EE | Estonian Applications | Protect (PR) | Govern (GV) | SI, PM | Estonian-specific applications, AI systems (Estonia-specific, no BSI counterpart) | (in APP) | — |

Cross-framework observations:

1. **DER → Detect/Respond → AU, IR**: Strongest alignment between E-ITS and NIST evidence-oriented constructs. Explains the highest direct log-verifiability rate (36.0%).
2. **ISMS → Govern → PM, PL**: Pure governance controls with 0% direct log-verifiability across all three frameworks.
3. **Protect function concentration**: Ten of twelve E-ITS module groups map to CSF Protect, but log-verifiability within Protect ranges from 4.2% (INF) to 16.9% (OPS), indicating that function-level analysis alone is insufficient for evidence planning.
4. **Estonian-specific modules**: SYS.EE and APP.EE map to NIST taxonomies without difficulty because CSF functions and SP 800-53 families are defined by control intent, not national context.

Abbreviations:

| Code | SP 800-53 family |
|---|---|
| AC | Access Control |
| AT | Awareness and Training |
| AU | Audit and Accountability |
| CM | Configuration Management |
| CP | Contingency Planning |
| IA | Identification and Authentication |
| IR | Incident Response |
| MA | Maintenance |
| PE | Physical and Environmental Protection |
| PL | Planning |
| PM | Program Management |
| PS | Personnel Security |
| RA | Risk Assessment |
| SC | System and Communications Protection |
| SI | System and Information Integrity |

Sources:

- [NIST CSWP 29, *The NIST Cybersecurity Framework (CSF) 2.0* (February 26, 2024)](https://doi.org/10.6028/NIST.CSWP.29)
- [NIST SP 800-53 Rev. 5, *Security and Privacy Controls for Information Systems and Organizations*](https://doi.org/10.6028/NIST.SP.800-53r5)
- [RIA, Estonian Information Security Standard (E-ITS)](https://www.ria.ee/en/cyber-security/management-state-information-security-measures)
