# Engineering Health

No single metric describes engineering performance. A useful health review combines delivery, quality, reliability, developer experience, and team sustainability, then uses trends to decide where leadership attention is needed.

## Balanced Signals

### Delivery

- Release or deployment frequency
- Roadmap predictability and milestone confidence
- Lead time for meaningful changes
- Pull-request review responsiveness
- Work blocked by cross-team dependencies

### Quality and Reliability

- Change failure rate
- Production defects and customer-reported issues
- Service stability and availability
- Incident volume, severity, and recurrence
- Time to acknowledge, mitigate, and learn

### Engineering System

- CI/CD pipeline reliability and duration
- Test automation coverage for critical paths
- Technical-debt trends and aged work
- Documentation quality and discoverability
- On-call load and repeated manual operations

### Team Health

- Satisfaction and wellbeing
- Sustainable workload and interruption pressure
- Retention and internal mobility
- Growth opportunities and feedback quality
- Psychological safety and decision clarity

## Review Approach

1. Review trends rather than isolated values.
2. Add qualitative context from engineers, product, support, and customers.
3. Identify one to three constraints that most limit outcomes.
4. Assign an owner and expected signal of improvement.
5. Revisit the decision at the next review.

## Important Guardrails

- Do not use commit counts, pull requests, or lines of code to rank individual engineers.
- Do not optimize one metric at the expense of the system. Faster releases with rising failure rates are not an improvement.
- Segment data when averages hide meaningful differences between services or workflows.
- Treat metrics as prompts for investigation, not automatic explanations.
- Make the purpose and interpretation of metrics transparent to the team.
