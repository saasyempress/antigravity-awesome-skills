# Skills Governance Policy

## Definition of a Skill
A skill is any executable capability, script, workflow, or automation
that Antigravity can invoke to perform work.

Not all code is a skill.
Only approved, promoted assets are skills.

---

## Skill Locations

### intake/
Raw ideas, experiments, drafts, and unvalidated concepts.
Nothing here is considered a skill.

---

### library/
Vetted, reviewed, and documented capabilities.
These may be considered candidate skills but are not active.

Skills in library/ are dormant.

---

### active/
Approved, production ready skills.
Anything in active/ is allowed to execute.

This folder must remain intentionally small.

---

## Promotion Requirements
Before a capability can move to active/, it must:
1. Have a clear purpose and description
2. Declare inputs and outputs
3. Be reviewed by a human
4. Be explicitly approved for execution

No automatic promotion is allowed.

---

## Execution Rules
- Antigravity may only execute skills from active/
- Antigravity may not self promote skills
- Antigravity must request approval before any execution

---

## Retirement Policy
Skills may be removed from active/ if they:
- Are unstable
- Are no longer needed
- Are replaced by better implementations

Retired skills should move back to library/ or be archived.

---

## Safety Principle
Fewer skills, better outcomes.
Explicit beats implicit.
Governance beats convenience.
