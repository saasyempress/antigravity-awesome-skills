# Autorun Output Contract

Purpose:
Define how autorun-generated outputs are produced, stored, and queued for human review.

Rules:
- Outputs are generated automatically from inbound content.
- Outputs are never published automatically.
- Outputs are written only to pipeline folders.
- Each output must retain a source reference.
- Each output must include a timestamp.

Allowed Output Locations:
- pipeline/05_autorun_outputs/briefs/
- pipeline/05_autorun_outputs/drafts/
- pipeline/05_autorun_outputs/quality_reviews/

Human QA Rules:
- Human review happens on Kara’s schedule.
- No output may advance stages without explicit approval.
- Rejected outputs remain archived for traceability.

This contract enforces safety, consistency, and human editorial control.
