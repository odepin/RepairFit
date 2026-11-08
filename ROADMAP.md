# RepairFit - development roadmap

**Status:** Planned work only. None of the boxes are marked completed. Estimates are rough.

## Product-level acceptance criterion

Every returned compatibility match can be traced to evidence, or is marked uncertain.

## Estimated work breakdown

| Step | Milestone | Estimated hours | Observable outcome |
|---|---|---:|---|
| 1 | Model part relationships and evidence | 9 | Stable identifier and provenance schema |
| 2 | Implement CSV import and normalization | 9 | Import refuses malformed and ambiguous references |
| 3 | Build fitment and supersession graph queries | 11 | Explanations identify evidence path |
| 4 | Implement contradictory-claim detection | 8 | Conflicts surface with their sources |
| 5 | Create search API and demo interface | 9 | Documented synthetic search cases |
| 6 | Tests and contributor documentation | 10 | Regression suite covers ambiguous fitment |
| | **Total estimated** | **56** | |

## Detailed milestones

### 1. Model part relationships and evidence (9 estimated hours)

- [ ] Deliverable: Stable identifier and provenance schema.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 2. Implement CSV import and normalization (9 estimated hours)

- [ ] Deliverable: Import refuses malformed and ambiguous references.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 3. Build fitment and supersession graph queries (11 estimated hours)

- [ ] Deliverable: Explanations identify evidence path.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 4. Implement contradictory-claim detection (8 estimated hours)

- [ ] Deliverable: Conflicts surface with their sources.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 5. Create search API and demo interface (9 estimated hours)

- [ ] Deliverable: Documented synthetic search cases.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

### 6. Tests and contributor documentation (10 estimated hours)

- [ ] Deliverable: Regression suite covers ambiguous fitment.
- [ ] Add tests or demonstrations proving the deliverable works.
- [ ] Record a genuine development commit and update documentation only after the work occurs.

## QA and release gates

- [ ] A real runnable implementation exists, with verified setup commands in `README.md`.
- [ ] Automated tests pass in a clean environment and failures are actionable.
- [ ] Only fabricated, original, openly licensed, or otherwise authorized sample data is published.
- [ ] No passwords, API keys, secrets, customer records, or employer/client confidential artifacts appear in repository history.
- [ ] A source-linked change log and actual progress notes distinguish finished work from plans.
- [ ] The GitHub history preserves authentic work and authorship; do **not** manufacture or backdate commits.

## Parking lot and risks

- Technical: Catalog licensing, quality and coverage are the principal business constraints.
- Commercial hypothesis (not validated): Licensed professional catalog features and supplier integrations.
- Beyond MVP: defer paid extensions and hosted features until the underlying product works.
