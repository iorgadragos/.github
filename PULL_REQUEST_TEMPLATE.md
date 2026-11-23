<!-- Org default PR template. Standards: iorgadragos/studio → docs/engineering/standards.md -->
## What & why
<!-- One logical change: what changes and why it is needed. -->

**Ticket:** Closes #… / Refs `iorgadragos/REPO#N`
- [ ] Ticket has acceptance criteria and its board fields set
- [ ] Non-trivial or hard-to-reverse change: design note / ADR linked
- [ ] New system or trust boundary: threat model (STRIDE) in `docs/architecture.md`

## How it was tested
- [ ] Automated tests added/updated (unit, integration, IaC, e2e, a11y as applicable); CI green
- [ ] Bug fix: regression test included
- [ ] UI change: browser e2e on desktop + mobile emulation
- [ ] Launch or major UI change (new page/flow, navigation/layout change): AI exploratory pass done, findings ticketed
- [ ] Manual / live checks: <!-- commands, URLs, screenshots -->

## Deployment & rollback
- [ ] Infra: `cdk diff` reviewed, no unexpected replacement (paste the summary below)
- [ ] Org- or account-wide AWS change: Dragos's explicit OK (link/quote)
- Rollback: <!-- how to undo -->

## Definition of Done
- [ ] Docs updated in this PR (README, architecture, ADR, runbook, CHANGELOG, CLAUDE.md as applicable)
- [ ] Security considered (IAM least privilege, secrets, inputs, dependencies, headers)
- [ ] Adversarial review done; every finding fixed or ticketed (summary below)

## Review summary
<!-- Add one row per review pass, until a pass finds nothing that needs fixing. -->
| Pass | Findings | Resolution (fixed / ticket #) |
|---|---|---|
| 1 | | |

## Post-merge (fill in a comment after merging)
- [ ] Deploy watched (run link)
- [ ] Verified live (URL / smoke output)
- [ ] Ticket closed with evidence
