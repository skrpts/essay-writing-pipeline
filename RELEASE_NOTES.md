# Release Notes

## v1.1.31
GH#818 Phase 1 (Tier 1) — fix intent-vs-output: the pipeline promised a drafted essay but polished the OUTLINE (the `essay-draft` prompt was shipped but never wired into the execution). Wire it in on a dedicated local `essay-drafting` skill: thesis → structure(outline) → **essay-draft(draft)** → polish. The polish step now binds `source` `from_step "Essay Drafting"` so it polishes the draft, not the outline. Coherent-lock all deps to current published (repin `polish-language` 1.0.1 → 1.0.5, etc.). contents skills 2→3.

## v1.1.30
GH#745 — declare per-step `output: {name, type}` on every execution step (thesis/text, outline/text, polished_essay/text, citations/list, compliance_verdict/decision, evidence_report/text). Lights up the #744 rich flow-map with named, typed outputs. Content-only; no bindings or logic changes.

## v1.1.29
GH#645 Row 3b — migrate to K-037 dep-referenced schema. Strip 14 inline shared-content files and declare 14 hub-shared deps (UUID id + slug name + version + checksum from `gen-dep-checksums.mjs`). Closes pre-Step-3 inline-vendoring for this bundle.

## v1.1.28
Wave 2: re-signed with canonical engine signing pipeline.

## v1.1.27
Tags migrated inline into manifest (GH#586). tags.yaml retired.

## v1.1.26
Bundle re-signed with canonical engine signing pipeline (Wave 2 migration).

## v1.1.25
Signature fix — RELEASE_NOTES.md now included in integrity checksum.

## v1.1.24
Initial catalog release with full structural and content-quality validation. All scanner checks pass.
