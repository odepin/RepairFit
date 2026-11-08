# RepairFit - technical plan

**Planning document, not an implementation report.**

## Product objective

A source-linked, confidence-aware compatibility graph, not an unverified shopping recommendation engine.

## Intended system boundary

- **Input:** Fictional appliances and fabricated part identifiers; licensed catalog support only when rights are verified.
- **Processing stages:** Part, device model, and relationship schemas; Source/provenance and confidence model; Conflict-detection and graph-query layer; Search API and demonstrator UI.
- **Output:** Every returned compatibility match can be traced to evidence, or is marked uncertain.
- **Runtime / build stack (tentative):** Python 3.12+, SQLite, FastAPI, SQLModel, pytest
- **Explicitly excluded:** Unlicensed scraping, copyrighted manual redistribution, warranty claims, or processing repair customers personal details.

## Functional modules

- Normalize public part numbers, aliases, and model identifiers
- Create explicit compatibility edges with source and confidence labels
- Expose explainable lookup paths across equivalents and supersessions
- Import authorized CSV catalogs and flag conflicting relationships
- Provide offline sample searches with seeded, invented catalog data

## Demonstration and acceptance cases

**Test 1:** Trace a synthetic old part to a documented successor

**Test 2:** Detect contradictory vendor fitment statements

**Test 3:** Search by appliance model and inspect evidence for a match

## Safety, privacy, and provenance

1. Keep example datasets fictional, self-created, or appropriately licensed.
2. Run locally for the initial prototype; do not collect data on actual third parties.
3. Document origin and versions of external specifications and dependencies.
4. Exclude production credentials; put environment variable *names* only in `.env.example` if required later.
5. Do not make certification, legal compliance, professional safety, or performance guarantees without independent validation.

## Engineering unknowns and constraints

Catalog licensing, quality and coverage are the principal business constraints.

## Release definition

A first release requires a runnable prototype, verified README instructions, automated tests tied to the three demonstrations, the full LICENSE file, and an honest public GitHub development history. The roadmap estimates are hypotheses until reviewed during implementation.
