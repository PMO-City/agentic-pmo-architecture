# Public publication contract

## Purpose

This repository publishes a readable public edition of PMO City's Agentic PMO reference architecture. It is a curated publication, not a mirror of the private authoring repository and not a dump of the internal requirements manuscript.

## Source boundary

The v1.0 public edition was prepared from the accepted PMO City Architecture v1.2.1 baseline. The public edition preserves the core meaning needed for public orientation while omitting internal implementation detail, exhaustive requirements, private deliberation, and material that has not been approved for public release.

The public repository does not make the internal source public. Internal source identity and checksums are retained in PMO City's publication records so that a future edition can be regenerated and reviewed against the same baseline.

## Editorial status

Public pages are explanatory unless they explicitly state otherwise. They may simplify, reorder, and illustrate the architecture for comprehension, but they must not:

- invent a new canonical definition;
- turn an aspiration into an evidence-backed claim;
- imply product certification or universal conformance;
- expose private source links or implementation details; or
- silently change the meaning of a released public edition.

## Reproduction workflow

```text
Internal architecture baseline
        ↓
Public-scope and omission map
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
- the internal source version;
- the publication date;
- the public scope and explicit omissions;
- the generator or editorial process used;
- review status; and
- known limitations.

## Versioning

Public v1.0 is the first public reading edition. A patch release may correct wording, links, or presentation without changing public meaning. A minor release may add backward-compatible public explanations. A major release may change the public model or its interpretation and requires migration notes.

Public version numbers do not replace the internal architecture version. Each release identifies both.

## Public source of truth

This repository is the source of truth for the public edition. The private PMO City architecture remains the source of truth for internal normative meaning, exact requirements, architecture decisions, and publication authorization.
