# tsuchifumi 土踏み

Evidence-honest observatory and system-dynamics actor for institutional earthing
access, ambient EMF exposure, and low-risk public-space relief. It treats
contested health claims as hypotheses, never diagnoses or sells products, and
uses aggregate regional data only.

This is the standalone west repository `etzhayyim/com-etzhayyim-tsuchifumi`.
EDN is canonical for identity, manifest, ontology, schema, seed data, and the
append-only observation ledger.

```bash
bb test
bb -m tsuchifumi.methods.analyze
bb -m tsuchifumi.methods.sysdyn
bb -m tsuchifumi.methods.risk
bb -m tsuchifumi.methods.coscientist
bb -m tsuchifumi.methods.viz
```

Implementation lives in `src/tsuchifumi/`, tests in `test/tsuchifumi/`, actor
schema in `schema/`, seed state in `data/`, and the generated self-contained
visualization in `public/viz/`.
