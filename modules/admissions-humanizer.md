# Admissions Humanizer

Run only after content audit. Humanization improves authenticity and readability without changing the essay's definition.

## Passes

1. Lock facts, ownership, technical terms, program fit, goals, and thesis using `references/HANDOFF_SCHEMA.md`.
2. Infer a voice range from genuine applicant samples: vocabulary, sentence complexity, directness, rhythm, and reflection style.
3. Mark each passage KEEP, REVISE, or REBUILD. Prefer KEEP when a sentence already works.
4. Remove AI-like architecture and admissions clichés using `references/AI_TELLS.md`.
5. Run `references/CONSULTANT_POLISH_GUARD.md` so polish stays within a believable applicant voice ceiling.
6. Recheck every lock and run `tests/humanizer-tests.md`.

Do not add slang, fragments, random variation, or grammar errors merely to appear human. Keep the applicant intelligent and clear. Detector highlights may identify repetitive or generic passages, but they do not override writing quality or factual integrity.
