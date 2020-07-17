# Relating to Stakeholders

## Stakeholder

...a person with an interest or concern in something, especially a business.

> In your project, you are a stakeholder!

`Exercise: List the stakeholders in your project`

## Customer Value-chain

![custvalue](images/value-chain-count-to-loyalty.png "customer value")

## Mapping Stakeholders

![value-chain](images/value-chain.png "value chain")

`Exercise: Map the stakeholder-value delivered by your project`

## Stakeholders Evolve

People change:

- After using the product, goals become clearer
- After using another product, expectations change

[The requirements are alive!](modeling-live-requirements.md)

## Obstacles to Evolution

### Complexity in Requirements

**Example** Requirement:
_The system shall notify the store-owner when their store gets full_

---

### Contradictions hidden by in Implementation and Ambiguity

**Sample** Contradiction: 
_The Store owner can delegate notifications._
_E.g., when owning a chain of stores._

---

### The Remedy

Try a [functional decomposition of business flows](modeling-business-flows.md)
to overcome these obstacles.

**Example**: A functional decomposition of the above user-login use-case

- System reports that the store is full when it measures x cust per sq ft
- System delivers reports to registered clients
- Transient failures shall be retried 3 times in a span of 30 minutes
