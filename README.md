# RepairFit

> Traceable compatibility mapping for appliance spare parts.

**Current state:** Documentation starter / proposed product. The presence of this README does **not** mean the software has been implemented, deployed, used. Update this status to reflect real work.

## What it is

RepairFit is a proposed specialist software tool for Independent repair technicians and specialty parts retailers. Part-number equivalences and machine compatibility are fragmented across manuals and vendor catalogs. The intended differentiation is: A source-linked, confidence-aware compatibility graph, not an unverified shopping recommendation engine.

## Intended users and use cases

- Trace a synthetic old part to a documented successor
- Detect contradictory vendor fitment statements
- Search by appliance model and inspect evidence for a match

## Planned features

- Normalize public part numbers, aliases, and model identifiers
- Create explicit compatibility edges with source and confidence labels
- Expose explainable lookup paths across equivalents and supersessions
- Import authorized CSV catalogs and flag conflicting relationships
- Provide offline sample searches with seeded, invented catalog data

## Proposed technology

Python 3.12+, SQLite, FastAPI, SQLModel, pytest

These technologies are *planned*, not a claim that dependencies have already been installed or code has been written. Revise this section when actual implementation decisions are made.

## Proposed architecture

- Part, device model, and relationship schemas
- Source/provenance and confidence model
- Conflict-detection and graph-query layer
- Search API and demonstrator UI

See [TECHNICAL_PLAN.md](TECHNICAL_PLAN.md) for technical boundaries and acceptance tests.

## Running locally

**Not yet runnable.** This package contains documentation templates, not software. When a functioning implementation is available, replace this paragraph with tested prerequisites, install instructions, a verified executable command, and a reproducible example using `Fictional appliances and fabricated part identifiers; licensed catalog support only when rights are verified.`

## Data boundaries and exclusions

Unlicensed scraping, copyrighted manual redistribution, warranty claims, or processing repair customers personal details. All public examples should use Fictional appliances and fabricated part identifiers; licensed catalog support only when rights are verified.

## Known limitations / validation risks

Catalog licensing, quality and coverage are the principal business constraints.

## Development roadmap

Work is broken into estimated, not-yet-completed milestones in [ROADMAP.md](ROADMAP.md). They are *planning estimates*, not an assertion that development has begun or that work will definitely be performed.

## Business direction

Potential commercial extensions: Licensed professional catalog features and supplier integrations. 

## Contributing and licensing

License: [Mozilla Public License 2.0](LICENSE) (`MPL-2.0`). The distribution contains the complete license text. Any future source files can include the SPDX identifier `MPL-2.0` and the Exhibit A notice where appropriate. Rights in contributions and project ownership must be verified before licensing.

