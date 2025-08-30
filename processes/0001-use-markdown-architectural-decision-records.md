# Use Markdown Architectural Decision Records

## Context

We want to record architectural decisions made in this project. Which format and structure should these records follow?

## Decision

We review some common templates like:

* [MADR](https://adr.github.io/madr/)
* [Michael Nygard's template](http://thinkrelevance.com/blog/2011/11/15/documenting-architecture-decisions)

We decide to use Michael Nygard's approach to be one of the leanest and more wide accepted.

## Consequences

Applying ADR on our project:

* ADR Folder: `/docs/adr/`
* Naming Format: `NNNN-title-with-dashes.md`

The filenames are following the pattern `NNNN-title-with-dashes.md`, where

* NNNN is a consecutive number.
* The title is stored using dashes and lowercase, because [adr-tools] also does that.
* The suffix is .md, because it is a Markdown file.`

In each ADR file, write these sections:

```markdown
# Title

## Status
What is the status, such as proposed, accepted, rejected, deprecated, superseded, etc.?

## Context
What is the issue that we're seeing that is motivating this decision or change?

## Decision
What is the change that we're proposing and/or doing?

## Consequences
What becomes easier or more difficult to do because of this change?
```
