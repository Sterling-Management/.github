---
name: Bug Report
about: Report a defect affecting a lottery platform or internal tool
title: "[BUG] "
labels: bug
assignees: ''

---

**Affected Lottery / Client**
Lottery code or name used to log in. For issues on a shared platform, also specify the affected client(s).

**Environment**
- [ ] Production
- [ ] Staging / UAT
- [ ] Development

**System Area**
Which area(s) are involved? (tick all that apply)
- [ ] Admin / Back Office
- [ ] Payments (DD, card, recurring)
- [ ] Draw Engine / Results
- [ ] Communications (email, SMS, push)
- [ ] Reporting / Exports
- [ ] Integrations (payment gateway, third-party API)
- [ ] Other: <!-- specify -->

**Describe the Bug**
A clear and concise description of what the bug is.

**Steps to Reproduce**
1. Go to '...'
2. Click on '...'
3. Observe '...'

**Expected Behaviour**
What should have happened instead.

**Actual Behaviour**
What actually happened. Include error messages or codes if available.

**Evidence**
Attach screenshots, screen recordings, or relevant log snippets.

**Impact & Urgency**
- Number of affected players/clients (if known):
- Is there a workaround? Yes / No
- Financial impact? Yes / No

**Risks**
- Could a fix introduce regressions elsewhere? Describe any known dependencies.
- Are there upcoming draws, payment runs, or deadlines that increase risk?
- Data integrity concerns (e.g. corrupted records, duplicate payments)?

**Rollback Procedure**
If a deployed fix causes further issues, what is the rollback plan?
- [ ] Revert the release/commit (no data migration involved)
- [ ] Feature flag — disable the change without redeployment
- [ ] Database rollback required (describe steps)
- [ ] Manual data correction needed
- [ ] No rollback possible — must fix forward
- Notes:

**Additional Context**
Link to Asana task, Smartsheet row, or support ticket if applicable.
