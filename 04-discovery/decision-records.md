# Decision Records

Traditional Product organizations often rely on lengthy Product Requirements Documents (PRDs) to communicate work.

While documentation is important, large documents frequently become outdated, difficult to maintain, and expensive to produce.

Instead of attempting to document everything, this playbook focuses on documenting the decisions that matter.

A Decision Record captures the context behind a decision so future teams understand not only **what** was decided, but **why**.

---

# What Is a Decision Record?

A Decision Record is a lightweight document that captures:

- The problem
- The decision
- Why the decision was made
- The alternatives considered
- The expected outcome

It serves as a durable reference throughout the life of a product.

---

# When to Create a Decision Record

Decision Records are valuable whenever a decision is expected to influence future work.

Examples include:

- New product initiatives
- Architectural changes
- Customer-funded development
- Strategic roadmap decisions
- Platform modernization
- Integration approaches
- Vendor selection
- Technical tradeoffs

Routine backlog items generally do not require Decision Records.

---

# Decision Record Template

## Problem Statement

Describe the problem being solved.

Avoid describing the solution.

Answer questions such as:

- What is happening today?
- Why is this a problem?
- Who is affected?

---

## Business Context

Explain why this work matters.

Examples include:

- Customer demand
- Revenue opportunity
- Compliance
- Strategic initiative
- Operational efficiency
- Platform investment

---

## Decision

Describe the decision that was made.

Keep it concise.

Example:

> Proceed with Engineering-led discovery using a phased cloud migration strategy.

---

## Alternatives Considered

Good decisions compare multiple options.

For each alternative include:

- Benefits
- Risks
- Cost
- Complexity

Documenting rejected options helps future teams understand why they were not selected.

---

## Assumptions

Every decision is based on assumptions.

Examples include:

- Customer behavior
- Available resources
- Technical constraints
- Market conditions
- Vendor capabilities

Assumptions should be reviewed throughout delivery.

---

## Risks

Identify known risks.

Examples include:

- Technical complexity
- Adoption challenges
- Integration dependencies
- Schedule uncertainty
- Operational impact

The goal isn't to eliminate risk.

The goal is to understand it.

---

## Success Measures

Define how success will be evaluated.

Examples include:

- Customer adoption
- Reduced support volume
- Performance improvements
- Revenue growth
- Deployment frequency
- Platform stability

If success cannot be measured, the decision should be revisited.

---

## Open Questions

Capture uncertainties that remain.

Examples:

- Additional customer validation
- Pending architecture review
- Regulatory clarification
- Third-party dependencies

Discovery continues until these questions are resolved—or the organization accepts the remaining uncertainty.

---

# Keep It Lightweight

Decision Records should communicate clearly without becoming burdensome.

A good Decision Record can often be completed in one or two pages.

The objective is clarity—not documentation for its own sake.

---

# AI Can Accelerate Decision Records

AI can assist by:

- Summarizing discovery meetings
- Drafting problem statements
- Identifying assumptions
- Highlighting risks
- Suggesting success metrics
- Comparing alternatives
- Generating executive summaries

Human judgment remains essential.

AI should accelerate documentation, not replace decision-making.

---

# Benefits

Well-maintained Decision Records help organizations:

- Understand why decisions were made.
- Onboard new team members faster.
- Reduce repeated discussions.
- Preserve organizational knowledge.
- Improve transparency.
- Create better executive communication.

Most importantly, they shift the focus away from writing large specifications and toward making thoughtful, well-informed decisions.

---

# Decision Record Example

| Section | Example |
|---------|---------|
| Problem | Pricebook updates take several hours to reach stores during peak processing. |
| Decision | Implement Engineering-led discovery to evaluate asynchronous processing. |
| Alternatives | Optimize current process, introduce queueing, redesign architecture. |
| Assumptions | Existing infrastructure can support distributed processing. |
| Risks | Additional operational complexity. |
| Success | Reduce average processing time by 75%. |

A Decision Record should tell the story of the decision clearly enough that someone joining the project six months later can understand both the reasoning and the expected outcome.

---

# Decision Record Checklist

Before approving a Decision Record, review the following questions.

## Problem

- [ ] Have we clearly defined the problem?
- [ ] Are we solving the root cause instead of a symptom?
- [ ] Do we understand who is affected?

---

## Business Value

- [ ] Why does this matter?
- [ ] What customer or business outcome are we trying to achieve?
- [ ] Does this align with our product strategy?

---

## Options

- [ ] Have we considered more than one approach?
- [ ] Have we documented the tradeoffs?
- [ ] Why was the selected option chosen?

---

## Assumptions

- [ ] What assumptions are we making?
- [ ] Have those assumptions been validated?
- [ ] What would cause us to change direction?

---

## Risks

- [ ] Have we identified the major technical risks?
- [ ] Have we identified the major business risks?
- [ ] What happens if we do nothing?

---

## Success

- [ ] How will we measure success?
- [ ] What metrics will improve?
- [ ] How will we know the investment was worthwhile?

---

## Communication

- [ ] Could someone joining this project six months from now understand why this decision was made?
- [ ] Is the recommendation clear?
- [ ] Have the appropriate stakeholders reviewed the decision?

---

# Final Question

Before moving into delivery, ask one final question:

> **If we made this decision today with the information we have, would we still feel confident explaining it six months from now?**

If the answer is "no," additional discovery may be needed.

The purpose of a Decision Record isn't to eliminate uncertainty. It's to ensure the organization makes informed, transparent, and intentional decisions.
