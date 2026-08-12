# Incident Learning

An incident review should explain how the system behaved, why the response made sense with the information available, and what will make future operation safer and faster.

## During the Incident

- Establish one incident commander and clear functional owners.
- Separate mitigation from diagnosis when customer impact is active.
- Maintain a timestamped decision and action log.
- State current impact, confidence, next action, and update time.
- Ask for help early when the incident crosses service or organizational boundaries.
- Preserve relevant telemetry, deployments, configuration changes, and communication artifacts.

## Review Questions

1. What user or business impact occurred?
2. How was the issue detected, and could it have been detected sooner?
3. What changed before the incident?
4. Which technical and organizational conditions allowed the impact?
5. What helped or slowed mitigation?
6. Which assumptions proved incorrect?
7. Where did safeguards work as designed?
8. What changes will reduce likelihood, blast radius, or recovery time?

## Actions That Matter

Strong actions change the system:

- Add an automated guardrail or validation.
- Improve observability around a missing signal.
- Reduce blast radius through isolation or staged rollout.
- Remove a recurring manual step.
- Clarify ownership or escalation.
- Exercise recovery through a drill.
- Improve a runbook with a tested decision path.

Weak actions depend mainly on memory, such as "be more careful."

## Leadership Behavior

Keep the review blameless without making it accountability-free. Individuals own actions and decisions; leaders own the conditions, priorities, incentives, and safeguards that shape those decisions. Track follow-up work alongside roadmap commitments so reliability investment remains visible.
