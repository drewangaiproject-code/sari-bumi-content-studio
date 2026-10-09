# Content Production Workflow

## Principle

Keep the workflow linear and visible. Each stage must have a defined input, output, and approval gate. Do not move forward merely because an AI role has produced an output.

## Stages

### 1. Owner brief
**Input:** product/SKU, objective, audience hypothesis, platform, format, duration/length, constraints, and references.

**Output:** a brief with missing facts and assumptions marked.

**Gate:** the brief is clear enough to write. Any product facts needed for the concept must be checked in `PRODUCTS.md`.

### 2. Content Writer
**Input:** approved brief and verified product facts.

**Output:** concept, hook, script/copy, caption, CTA, and any factual assumptions or questions. For Reels, include time-coded beats when requested.

**Quality criteria:** natural Indonesian, specific hook, coherent tension/payoff, clear relevance to the product, no unsupported claims, and no invented facts.

### 3. Owner copy approval
**Input:** Writer output.

**Output:** an explicitly approved copy version or a list of requested revisions.

**Gate:** no storyboard, SVG, or animation production before the Owner approves the copy. Draft status labels or another agent's recommendation do not count as Owner approval.

### 4. Visual & Motion
**Input:** approved copy, verified brand references, and reviewed legacy assets if any have been approved for use.

**Output:** storyboard, visual direction, scene timing, SVG/motion implementation plan, and required asset list.

**Quality criteria:** the visual serves the copy, text is legible, branding is consistent, and no unapproved legacy asset is treated as approved.

### 5. Quality Control
**Input:** candidate final visual/export and its approved copy.

**Output:** pass/fail checklist and explicit issues to fix.

**Checks:** factual consistency, claims, copy match, spelling, brand identity, contrast/readability, dimensions/timing, missing assets, and export integrity.

**Gate:** a failed check returns to the relevant stage; it must not be marked final.

### 6. Owner final approval
**Input:** QC-passed candidate and review notes.

**Output:** explicit approval or revision request.

**Gate:** only Owner-approved outputs are marked `FINAL_APPROVED`. QC pass alone is not final approval.

## Required status vocabulary

Use clear statuses and avoid contradictory labels:
- `BRIEF_DRAFT`
- `BRIEF_READY`
- `COPY_DRAFT`
- `COPY_REVISION_REQUIRED`
- `COPY_APPROVED`
- `STORYBOARD_DRAFT`
- `VISUAL_IN_PROGRESS`
- `QC_FAILED`
- `QC_PASSED`
- `FINAL_APPROVED`
- `ON_HOLD`

Only the Owner can approve copy and final deliverables. A status must reflect the latest explicit decision; a newer withdrawal or revision request overrides an older approval.

## File and version handling

- Keep one clearly identified current version per content item.
- Retain old drafts as history/reference; do not silently promote them to approved.
- Record the product, content ID, version, status, and approval decision in the content record or its accompanying notes.
- Keep outputs separate from briefs and reference assets.
- Do not overwrite owner-provided brand assets.
- Do not import legacy assets until an inventory entry has been reviewed and approved.

## Initial pilot

Use P01 — Jamu Kunir Asam as the first pilot only after its relevant product facts are verified. Evaluate the Writer against prior drafts as a benchmark, not as approved copy. Do not start visual production until the Owner explicitly approves the selected copy.

## Automation boundary

This workflow is tool-agnostic. Repository setup does not authorize running Hermes, connecting Telegram, launching agents, publishing content, or introducing new automation. Those steps require separate explicit approval.
