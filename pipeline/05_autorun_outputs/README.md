# 05_autorun_outputs

Purpose:
This folder holds machine generated outputs created automatically from intake content.

What happens here:
- Raw intake is analyzed
- Briefs are generated
- Drafts are generated
- Quality review artifacts are generated

Subfolders:
- briefs: machine generated content briefs
- drafts: machine generated first pass content
- quality_reviews: self checks, compliance checks, and scoring artifacts

Rules:
- No human editing occurs in this folder
- Outputs are append only
- Files are time stamped and source linked
- Nothing here is considered final

Downstream:
Outputs from this folder are reviewed in 30_review.
Only approved content moves forward.
