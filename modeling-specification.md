# Requirements and Specifications

Specification: an act of identifying something precisely

## The Quality of a Requirement

<!-- markdownlint-disable MD033 -->

<table>
<tr><td>Essential</td><td>Implementation-free</td><td>Unambiguous*</td>
</tr>
<tr><td>Consistent</td><td>Complete</td><td>Singular*</td>
</tr>
<tr><td>Feasible</td><td>Traceable</td><td>Verifiable*</td>
</tr>
</table>

> Make it Verifiable. Then pursue completion.

`Exercise: Critique this- "The device shall sync to the backend when online. It shall store footfalls temporarily when offline"`

- Sync time - when? = Ambiguous
- Temporary = how long? = Ambiguous
- Store = where to store? = Ambiguous (store in Volatile = power outage / store too long = outdated data gets sync)
- Sync = what to sync? count? time of entry? ... = Not Complete
- Not Singular - hard to read; incomplete conditions
- What is lacking?

`Exercise: Critique this- 

"The system shall notify the store-owner when store gets full"

"Store is full when x cust per sq ft"

"Notification is through SMS"

"Configuration is in system config"

"Failure of notification triggers retry, max 3 times over 4 hours"`

- SMS number configured where? = Ambiguous / Not verifiable
- What is full? = Ambiguous
- What to notify / content of the notification = Complete
- Notification failure = how many times retry? = "Three times over 4 hours"
- What is lacking?

## *Specification

> A complete specification is [expensive](form-fit-function.md).
Use [Analogies](modeling-needs-analogy-structure.md)
for guidance. Relate them to all stakeholders.

## The way forward

- Mind on the Customer's context
- Write for your Audience

[Who is my Audience?](modeling-needs-of-stakeholders.md)
