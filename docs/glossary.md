# Glossary

Core terminology for data, metrics, and analytics concepts.

---

## Active User
A user who performs at least one meaningful action within a defined 
time period (daily, weekly, or monthly).

**Related metrics:** [Engagement Rate](metrics/engagement.md)

---

## Cohort
A group of users who share a common starting point — typically their 
first use of a product within the same time window.

Cohort analysis tracks how different groups behave over time, making 
it possible to compare retention across periods.

**Related metrics:** [Retention Rate](metrics/retention.md)

---

## Churn Rate
The percentage of users who stop using a product within a given period.

$$
\text{Churn Rate} = 100 - \text{Retention Rate}
$$

High churn indicates users are not finding sustained value.

---

## Data Catalog
A structured inventory of an organization's data assets — including 
datasets, metrics, pipelines, and their relationships.

A good data catalog answers three questions:
- What data exists?
- What does it mean?
- Who owns it?

---

## Metric
A quantifiable measurement used to evaluate performance, behavior, 
or system state against a defined goal.

A well-defined metric always includes:
- A clear definition
- A calculation method
- An owner
- A known limitation

---

## Ontology
A formal representation of concepts within a domain and the 
relationships between them.

In data systems, ontologies provide the semantic layer that makes 
data interpretable across teams and tools — defining not just 
what something is called, but what it *means*.

---

## Session
A single continuous period of user activity within a product, 
bounded by inactivity or logout.

Session length and depth are common inputs to engagement calculations.

---

## Schema
The formal structure that defines how data is organized — 
field names, types, relationships, and constraints.

Schemas are the contract between data producers and data consumers.