# AMBASSADOR-OWNED VALIDATOR PROGRAM

> **Pilot — one validator slot.**

---

### What

A single Orbinum validator node out of 32 active validator-set, operated collectively by a small cohort of Ecosystem Agents. The cohort runs the node, and the node's staking emissions fund the agent reward pool.

### Why

Three reasons, in order of importance.

1. **Rewards should come from emissions.** Ambassador programmes usually get funded out of a treasury, which means they compete with engineering for cash. This one pays for itself out of the 30% of supply already allocated to staking rewards.
2. **It decentralises the validator set as a side effect.** Orbinum's validator set is currently permissioned and small. Handing one slot to the community is the first real step toward a set that is not entirely core-team-operated.
3. **Ownership beats point farming.** An agent who co-operates a node has a reason to care about uptime, upgrades and network health. That is a different relationship than completing weekly tasks for credits.

### Scope of the pilot

**One slot. One node. One cohort.** We are deliberately not launching this at scale.

A validator that goes down, misses upgrades or gets slashed damages the network and the programme at once. We would rather run one node well for two quarters and learn what breaks than run five badly. Expansion is reviewed at the end of the pilot, and only then.

---

## How it works

### Phase 1 — Before mainnet

The node does not exist yet. During this phase:

1. The cohort is selected and onboarded.
2. The cohort runs a **testnet validator** as preparation, using the same runbook that will govern the mainnet node.
3. The operating runbook, monitoring setup, on-call rota and incident procedure are written and tested by the cohort itself.
4. VAL task points accrue as ORB Credits under the [Ecosystem Agent Program](./ecosystem-agent-program.md) scoring, same as any other task.

Phase 1 exists so that nobody touches a mainnet key without having already operated a node for a full quarter.

### Phase 2 — After mainnet

1. The core team allocates one validator slot to the cohort.
2. The node earns staking emissions like any other validator.
3. Emissions from this node form the **Ambassador Reward Pool**, replacing the credit-based pool used before TGE.
4. The pool is distributed using the existing monthly scoring — achievement percentage, surplus rules and quarterly bonus all unchanged.

---

## Emissions are finite — read this before you join

Orbinum has a **hard cap of 1,000,000,000 ORB**. There is no perpetual inflation, and this programme is not funded by one.

The Staking Rewards allocation is 30% of supply (300,000,000 ORB). It is not pre-allocated — it is emitted per block as validators and nominators secure the network, **over roughly 10 years** from mainnet. Circulating supply reaches the full cap over approximately that same period.

Three consequences that every cohort member and every agent should understand up front.

**1. The pool is largest early and shrinks over time.** Rewards per month are highest in the first years and decline as the emission schedule runs down. Nobody should join expecting a flat income.

**2. One node's share falls as the validator set grows.** Emissions are split across the active set. The set is currently 5 and can reach 32. As it fills, the share earned by any single node — including this one — decreases. The pool is therefore not fixed even within the early years, and the monthly reward pool figure will be republished each quarter rather than fixed once.

**3. The pool has an end date.** When staking emissions are exhausted and supply is fully circulating, validator income transitions away from emissions. At that point the funding mechanism for this programme **does not automatically continue** — it will be renegotiated with the core team and the community, and a new model agreed and published before the old one ends. We are committing to hold that conversation in the open and in advance, not to a specific outcome we cannot yet responsibly promise.

---

## Cohort

**Size:** 3 to 5 agents. Small enough to coordinate, large enough to cover a rota across time zones.

**Selection:**
- Previously a community moderator or Minimum one completed month in the Ecosystem Agent Program (trial period counts).
- Quarterly average score ≥80%.
- Demonstrated technical capability — prior node operation, sysadmin experience, or completion of the Phase 1 testnet node setup.
- Time-zone spread is a selection factor. A cohort that is all in one region cannot hold a rota.

**Rotation:** Reviewed each quarter. An agent who drops below 80% average, or who misses on-call duties twice, returns to the standard programme and the seat is reopened.

---

## Keys, custody and slashing

This is the part that has to be unambiguous, so it is stated plainly.

- **Ambassadors operate the node. They do not hold the stash key.** The stash remains with the core team. Session keys are rotated and held by the operating cohort.
- **The core team bears slashing risk during the pilot.** The cohort is not personally liable for a slash. This is deliberate: asking unpaid community members to carry financial liability for infrastructure would select for the wrong people and would be unfair.
- **A slash still has consequences.** A slashing event triggers an immediate incident review and suspends reward distribution from the node until the cause is resolved and the runbook is amended.
- **Any cohort member may escalate to the core team at any time, for any reason, without penalty.** Nobody should feel they have to solve an incident alone to protect their standing in the programme.

---

## Operating requirements

| Item | Requirement |
| --- | --- |
| Uptime target | ≥99.5% monthly |
| On-call coverage | 24/7 across the cohort rota |
| Incident acknowledgement | Within 30 minutes during your on-call window |
| Monitoring | Agreed alerting stack, alerts routed to the cohort channel and the core team |
| Upgrades | Applied within the window announced by the core team |
| Reporting | Monthly uptime and incident summary, published as an issue on this repository |
| Runbook | Maintained by the cohort, reviewed by the core team each quarter |

---

## Reward distribution

The node's emissions go to the Ambassador Reward Pool. The pool is then distributed across the **whole Ecosystem Agent Program**, not only the validator cohort.

This is intentional. The validator funds the programme; it is not a private income stream for the people who happen to hold the seat. Cohort members earn their share through the VAL optional task like any other task, at the same 25-point ceiling.

If the pool exceeds what the monthly scoring distributes, the surplus rules in the Ecosystem Agent Program apply unchanged: equal distribution to those who achieved ≥80%, and if nobody did, it remains in the Community Treasury.

---

## Review

The pilot is reviewed at the end of its second full quarter of mainnet operation. The review covers:

- Uptime and incident record against target.
- Whether emissions covered the reward pool, and by what margin.
- Whether cohort rotation worked or concentrated on one or two people.
- Whether the runbook held up under real incidents.

Expansion beyond one slot is decided at that review, published on this repository, and not before.

---
Updated on the 16th September 2026
