# Maintainer triage

Public reports are evidence to review, not implementation authorization. No form, label or milestone automatically launches an agent, merges code or publishes a release. Source implementation belongs in the private source repository under its branch and approval policy.

## Reusable public triage comment

Copy this into the public issue after review. Keep private diagnostic links, identifiers, report contents and internal source details in the private tracking issue rather than this comment.

```markdown
### Triage

- Reproduction: Not checked / Reproduced / Needs more information / Not reproduced
- Affected app version:
- Affected feature:
- Summary of confirmed behavior:
- Private diagnostics reviewed: Not available / Pending / Reviewed
- Missing public reproduction details:
- Implementation approval: Not approved / Approved by the owner for the scope below
- Approved scope and acceptance conditions:
- Focused verification plan:
- Target milestone: Unassigned; not a delivery-date commitment
- Next step:
```

## Labels and next steps

- Forms apply `bug` or `enhancement` plus `needs-triage` initially.
- Add the appropriate `area: ...` label after reviewing the affected feature. Form dropdown values do not automatically add area labels.
- Use `needs-info` when reproduction details are missing, and `confirmed` only after reproduction or other concrete evidence. Remove `needs-triage` once an initial review is complete.
- Search for an existing report before creating a private implementation task. Link public duplicates to their existing public report; do not copy private diagnostics into the public thread.
- The owner deliberately chooses implementation approval, milestone and any agent assignment. A confirmed bug or selected milestone alone does not authorize coding or promise a delivery date.
- Record private diagnostic linkage and sensitive technical details only in the private tracker. Reports with personal data should be handled promptly without repeating that data in comments.
- Close a report with a short public explanation when fixed, duplicated or otherwise resolved. Link the shipped public release when applicable.

Milestones and a project board can be added when approved work warrants them. This setup does not create release commitments or automatically assign incoming reports.
