# Phase 00 — Rules of Engagement & Responsible Testing

> Before learning how to find vulnerabilities, learn where and how you are allowed to test.

## Objective

Understand the legal, ethical, and operational boundaries of authorized security testing.

---

## Learning Checklist

### Scope

* [ ] Understand what "in scope" means
* [ ] Understand what "out of scope" means
* [ ] Identify exact assets covered by a program
* [ ] Understand wildcard domains
* [ ] Understand excluded subdomains/assets
* [ ] Check whether APIs/mobile applications are included
* [ ] Read the complete program policy before testing

### Safe Harbor

* [ ] Understand what safe harbor means
* [ ] Understand that safe harbor does not automatically mean every action is permitted
* [ ] Follow the program's specific testing rules
* [ ] Understand prohibited activities

### VDP vs Bug Bounty

* [ ] Understand Vulnerability Disclosure Programs (VDPs)
* [ ] Understand Bug Bounty Programs
* [ ] Understand whether monetary rewards are offered
* [ ] Understand disclosure expectations
* [ ] Understand program-specific rules

### Rate Limits

* [ ] Understand request-rate restrictions
* [ ] Identify program-defined limits
* [ ] Avoid aggressive automated requests
* [ ] Understand the risk of service degradation

### Automated Scanning

* [ ] Check whether automated scanning is permitted
* [ ] Check which tools/scanners are prohibited
* [ ] Understand rate limits for automation
* [ ] Avoid unrestricted scanning of production systems
* [ ] Prefer controlled testing

### Sensitive Data

* [ ] Understand what constitutes sensitive information
* [ ] Minimize access to sensitive data
* [ ] Do not download unnecessary data
* [ ] Do not modify or delete user data
* [ ] Safely document evidence
* [ ] Follow the program's disclosure requirements

### Responsible Disclosure

* [ ] Understand responsible disclosure
* [ ] Understand coordinated disclosure
* [ ] Learn how to submit a vulnerability report
* [ ] Avoid public disclosure before authorization
* [ ] Follow the program's communication process

### Duplicate Reports

* [ ] Understand duplicate vulnerabilities
* [ ] Understand why reports can become duplicates
* [ ] Learn how to search existing disclosures where permitted
* [ ] Focus on unique impact and root cause

### Informational Findings

* [ ] Understand informational findings
* [ ] Understand low-impact vulnerabilities
* [ ] Distinguish security weaknesses from observations
* [ ] Understand program-specific reward criteria

### Impact vs Severity

* [ ] Understand vulnerability severity
* [ ] Understand business impact
* [ ] Learn the basics of CVSS
* [ ] Understand exploitability vs impact
* [ ] Learn how vulnerability chaining can increase impact

---

## Core Principle

Never test a target simply because it is technically accessible.

Before testing:

1. Read the program policy.
2. Confirm the asset is in scope.
3. Confirm the testing method is permitted.
4. Check rate limits.
5. Check prohibited actions.
6. Minimize impact.
7. Stop if testing becomes unsafe or unauthorized.

---

## My Notes

### What I learned

<!-- Add your notes here -->

### Questions

<!-- Add questions here -->

### Important Lessons

<!-- Add important concepts here -->

### Resources

* PortSwigger Web Security Academy
* OWASP Web Security Testing Guide
* Bug bounty platform program policies
* Vulnerability Disclosure Program policies

---

## Completion Criteria

I consider this phase complete when I can:

* Explain scope and out-of-scope assets
* Explain VDP vs Bug Bounty
* Explain safe harbor
* Read a program policy before testing
* Identify prohibited testing activities
* Explain rate limits
* Explain responsible disclosure
* Explain duplicate reports
* Explain informational findings
* Explain impact vs severity

**Status:** `Not Started`

**Started:** YYYY-MM-DD

**Completed:** YYYY-MM-DD
