# Lab 01 — Governance Baseline

## Business reason
Create a small Azure governance baseline that can be reused as the foundation for later labs and portfolio projects.

## Objectives
- Organize Azure resources cleanly
- Apply consistent tags
- Understand scoped RBAC
- Configure basic cost controls
- Practice documenting operational intent

## Planned resources
- Resource group: `rg-lab-governance-01`
- Tags:
  - `Project=AZ104`
  - `Environment=Lab`
  - `Owner=BJ`
  - `DeleteAfter=<date>`

## Tasks
- [ ] Create the resource group
- [ ] Apply tags
- [ ] Review built-in Azure roles
- [ ] Assign one scoped role in a safe lab context
- [ ] Create an Azure budget alert appropriate to the subscription
- [ ] Document what each control protects against
- [ ] Intentionally create one safe misconfiguration
- [ ] Troubleshoot and validate the fix
- [ ] Record cleanup steps

## Failure test
Describe one safe governance or access problem you create intentionally.

## Diagnosis
Record evidence, hypotheses, and the order in which you ruled causes in or out.

## Fix and validation
Document the exact fix and how you proved the expected behavior returned.

## Cost and cleanup
Delete unused resources and note anything that may continue to incur cost.

## Interview story
Use:

**Situation → Impact → Assessment → Action → Validation → Prevention**

Suggested closing line:

> I didn’t just configure the resource; I added governance, validation, and cleanup so the environment was repeatable and easier to operate.
