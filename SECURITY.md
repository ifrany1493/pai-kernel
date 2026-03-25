# Security Policy
## PAI-Kernel · PAI Constitutional Document (PAI-CD)

---

## Scope

PAI-Kernel is a normative governance standard, not a software product. Security disclosures in this context cover:

- **Specification vulnerabilities** — loopholes, ambiguities, or gaps in the normative corpus that could be exploited to circumvent PAI-CD protections while claiming compliance.
- **Reference implementation vulnerabilities** — security issues in the PAI-Kernel SDK (MAD-TR codebase) once published.
- **Conformance Suite gaps** — cases where a non-compliant implementation could pass the conformance tests.

---

## Responsible disclosure

If you have identified a specification vulnerability, a reference implementation security issue, or a conformance gap:

**Do not open a public GitHub Issue.**

Contact us privately first:

**Email:** `contact@paikernel.org`  
**Subject line:** `[SECURITY] Brief description`

We will acknowledge receipt within 72 hours and work with you on a coordinated disclosure timeline.

---

## What to include

- The specific clause, invariant, or component affected.
- A description of the vulnerability: how it can be exploited, what protection it circumvents.
- If applicable: a proof-of-concept or test case demonstrating the issue.
- Your assessment of severity and urgency.

---

## Process after disclosure

1. We assess the report and confirm whether it constitutes a genuine vulnerability.
2. For specification vulnerabilities: we initiate an Amendment procedure (expedited if severity warrants).
3. For implementation vulnerabilities: we prepare a fix and coordinated release.
4. We credit the reporter in the relevant Amendment or release notes, unless anonymity is requested.

---

## Out of scope

- Issues with third-party implementations of PAI-CD that are not maintained by PAI-Kernel.
- Theoretical attacks requiring physical access to infrastructure.
- Social engineering attacks on project contributors.

---

## Philosophy

PAI-CD's Principle 3 (Anti-Manipulation) requires that the standard acknowledge its own limitations honestly. If our specification has a gap, we document it as a finding — we do not conceal it.

The same principle applies here: if you find a real vulnerability, we want to know about it and we will be transparent about how we address it.

---

*PAI-Kernel · paikernel.org · contact@paikernel.org*
