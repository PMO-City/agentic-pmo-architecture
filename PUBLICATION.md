# Public publication contract

## Purpose

This repository is the canonical public publication of PMO City's Agentic PMO reference architecture. It is intentionally focused and readable; it is not a dump of an internal requirements manuscript.

## Source boundary

The public edition preserves the concepts, boundaries, operating model, examples, and conformance guidance approved for public use. It omits private implementation detail, exhaustive requirements, private deliberation, and material outside the public scope.

Future material may be prepared from private working documents, but the public repository is the maintained authority for the public edition. A private working document does not silently replace or revise a released public version.

## Editorial status

Public pages are explanatory unless they explicitly state otherwise. They may simplify, reorder, and illustrate the architecture for comprehension, but they must not:

- invent a new canonical definition;
- turn an aspiration into an evidence-backed claim;
- imply product certification or universal conformance;
- expose private source links or implementation details; or
- silently change the meaning of a released public edition.

## Reproduction workflow

```text
Public scope and omission map
        ↓
Public narrative, definitions, and worked examples
        ↓
Privacy, consistency, accessibility, and link checks
        ↓
Architecture-owner review
        ↓
Editorial review
        ↓
Public release tag
```

Every public release should record:

- the public version;
- the publication date;
- the public scope and explicit omissions;
- the generator or editorial process used;
- review status; and
- known limitations.

## Versioning

Public v1.0 was the first public reading edition. Release v1.0.1 establishes the canonical public edition. A patch release may correct wording, links, licensing, or presentation without changing public meaning. A minor release may add backward-compatible public explanations. A major release may change the public model or its interpretation and requires migration notes.

Public version numbers are the version authority for this repository. There is no second public version hidden behind an unpublished source.

## Public source of truth

This repository is the source of truth for the public edition. PMO City remains responsible for architecture stewardship, review, publication decisions, and the boundaries of what is presented as public.
