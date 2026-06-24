---
name: Data Export Request
about: Request a new or modified data export for a client
title: "[Export] "
labels: enhancement, export
assignees: ''

---

**Client(s)**
Lottery code/name, or "All" if platform-wide.

**Export Type**
- [ ] Member / Player data
- [ ] Payment transactions
- [ ] Direct Debit file
- [ ] Draw results / winners
- [ ] Communications log
- [ ] Attrition / Cancellations
- [ ] Claw-back / Failed payments
- [ ] Financial reconciliation
- [ ] Other: <!-- specify -->

**Requirements Summary**
Describe what the export should contain, including key fields, filters, and date ranges.

**Output Format**
- [ ] CSV
- [ ] Excel (.xlsx)
- [ ] PDF
- [ ] API / automated feed
- [ ] Other: <!-- specify -->

**Frequency**
- [ ] One-off
- [ ] Daily
- [ ] Weekly
- [ ] Monthly
- [ ] On demand (manual trigger)

**Delivery Method**
- [ ] Download from Admin portal
- [ ] Email to specified recipients
- [ ] SFTP / secure transfer
- [ ] Other: <!-- specify -->

**Deadline**
Is there a hard deadline? If so, specify date and reason.

**Risks**
- Does this export contain sensitive/PII data? What controls are needed?
- Could the export run impact system performance (large dataset, peak hours)?
- Are there GDPR or data-sharing agreement constraints?
- If automated, what happens if the export fails silently?

**Rollback / Failure Procedure**
If the export delivers incorrect data or fails, what is the recovery plan?
- [ ] Re-run the export with corrected parameters
- [ ] Notify recipients to discard the file and re-issue
- [ ] Revoke access / delete the delivered file
- [ ] Pause automated schedule until investigated
- [ ] No action needed (one-off, low sensitivity)
- Notes:

**Additional Context**
Asana task, Smartsheet link, or sample file showing desired layout.
