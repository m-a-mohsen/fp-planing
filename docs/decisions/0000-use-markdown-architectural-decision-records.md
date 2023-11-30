# Use Markdown Architectural Decision Records

* Status: Proposed
* Deciders: Mo
* Date: 2023-11-30

## Context and Problem Statement

We want to record architectural decisions made in this project.
Which format and structure should these records follow?

## Decision Drivers

* {decision driver 1, e.g., a force, facing concern, …}
* {decision driver 2, e.g., a force, facing concern, …}

## Considered Options

* [MADR](https://adr.github.io/madr/) 2.1.2 – The Markdown Architectural Decision Records
* [Michael Nygard's template](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions) – The first incarnation of the term "ADR"
* [Sustainable Architectural Decisions](https://www.infoq.com/articles/sustainable-architectural-design-decisions) – The Y-Statements
* Other templates listed at <https://github.com/joelparkerhenderson/architecture_decision_record>
* Formless – No conventions for file format and structure
* {title of option 1}
* {title of other option}

## Decision Outcome

Chosen option: "MADR 2.1.2", because

* Implicit assumptions should be made explicit.
  Design documentation is important to enable people understanding the decisions later on.
  See also [A rational design process: How and why to fake it](https://doi.org/10.1109/TSE.1986.6312940).
* The MADR format is lean and fits our development style.
* The MADR structure is comprehensible and facilitates usage & maintenance.
* The MADR project is vivid.
* Version 2.1.2 is the latest one available when starting to document ADRs.

### Positive Consequences

* {e.g., improvement of one or more desired qualities, …}
* hello

### Negative Consequences

* {e.g., compromising one or more desired qualities, …}
* there

## Pros and Cons of the Options

### MADR 2.1.2

GHstars: 300, last updated

* Good, because yes
* Good, because neutral
* Bad, because true

### {title of option 1}

{example | description | pointer to more information | …}

* Good, because {argument a}
* Good, because {argument b}
* Neutral, because {argument c}
* Bad, because {argument d}

### {title of other option}

{example | description | pointer to more information | …}

* Good, because {argument a}
* Good, because {argument b}
* Neutral, because {argument c}
* Bad, because {argument d}
* …
