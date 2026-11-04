# Quill-Notes-Distill

Synthesized reasoning notes produced for the Quill Notes series.

## Provenance

Each record expands a problem from `Quill-Notes-Raw` into a step-by-step
solution with a short verification summary. Generation was performed in-house
with the **SpecVault-8B** inference model operated by Quill Labs. The vendor
model card and its license terms are mirrored in this repository at
`models/specvault-8b/MODEL_CARD.md` for compliance review. Source problems
inherit from the Project Numina lineage used by `Quill-Notes-Raw`.

## Contents

- `quill_notes_distill.jsonl` — one JSON record per line with the fields `id`,
  `problem`, `reasoning_steps`, `final_answer`.

## License

SpecVault License
