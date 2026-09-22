# How to Use These Resources With Coding Agents

The point of these files is to make your decisions visible before an agent starts changing the project. Adapt them to your work; do not hand an agent several blank templates and expect it to decide what they mean.

## The workflow

1. Fill in the [project brief](templates/project-brief-template.md). Decide who the site is for, what it should do and what each page is for.
2. Fill in the [source of truth](templates/source-of-truth-template.md). Record approved facts, wording, assets, addresses and design rules.
3. Adapt the [agent instructions](templates/agent-instructions-template.md). State where the agent may work, what is already decided and what it must not change.
4. Give those completed files to the coding agent before asking for implementation.
5. Ask the agent to inspect the project before editing. It should report the relevant structure, constraints and any conflict it finds.
6. Build on a non-production branch. Save the current known-good state first.
7. Review the preview manually on desktop and mobile. A passing build is not a visual judgement.
8. Run the relevant [checklists](checklists/pre-build-checklist.md), especially the visual, consistency, security and pre-release checks.
9. Review the changed-file list and the actual diff. Compare what changed with what you asked for.
10. Publish deliberately. Know whether approving or merging will trigger production automatically.
11. Open the real public address and verify the live result.
12. If the result is wrong, stop changing it and follow the [rollback checklist](checklists/rollback-checklist.md).

## Example prompts

### Inspect before editing

> Read the completed project brief, source of truth and agent instructions. Inspect the relevant project files. Report the pages and shared components this request touches, any conflict between the request and the source of truth, and the files you expect to change. Do not edit anything yet.

### Make one decided change

> On the training page, move the evidence block above the programme explanation. The wording, heading and images are approved and must not change. Change nothing below the evidence block. Work on a non-production branch and do not publish. List changed files and observations separately.

### Review without manufacturing work

> Check the page at 1440, 768, 390 and 360 pixels wide for overflow, broken layout and first-screen hierarchy. If nothing is genuinely wrong, make no changes and report that. List subjective concerns separately from confirmed defects.

### Compare across pages

> Compare the evidence heading, CTA wording and role description across all public pages. Classify each difference as Wrong, Drifted or Deliberate. Do not change anything. For every Deliberate difference, identify where the reason is documented.

### Prepare to release

> Run the pre-release checklist. Report each item as passed, failed or not verified, with evidence. Do not publish. Tell me whether approval or merge would automatically deploy to production and identify the rollback point.

## Keep the roles separate

Use an assistant to discuss options or review work if that helps. Use a coding agent to inspect and change the project. In both cases, the human owner decides the purpose, facts, design, scope and release.
