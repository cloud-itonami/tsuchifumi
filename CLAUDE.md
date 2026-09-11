# com-etzhayyim-tsuchifumi repository rules

- This is an independent flat-path west repository.
- EDN is canonical. Do not commit JSON, JSON-LD, or BPMN outside `wire/`.
- Keep code in `src/tsuchifumi/`, tests in `test/tsuchifumi/`, actor-owned schema
  and ontology in `schema/`, seed state in `data/`, and generated visualization
  in `public/viz/`.
- Do not reintroduce Go, TinyGo, shell launchers, or former monorepo paths.
- Preserve evidence-tier honesty, non-diagnostic behavior, aggregate-only data,
  no-commerce, distribution-only modeling, and no-server-key invariants.
- Run `kbb -M:test` before publishing changes.
