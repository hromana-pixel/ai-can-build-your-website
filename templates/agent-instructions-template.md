# Agent Instructions

Adapt this file before giving it to a coding agent. Delete sections that do not apply. Do not leave placeholders that the agent could mistake for decisions.

## Project purpose

- **The site is for:**
- **The visitor should:**
- **The core claim is:**
- **The approved source of truth is:**

## Human owner responsibilities

The human owner decides and approves:

- purpose and page jobs
- factual and commercial claims
- design direction and subjective visual judgement
- scope and priority
- legal, privacy, licensing and publication decisions
- whether the work is released

The agent may report that a human or professional decision is required. It may not make that decision by inference.

## What the coding agent may change

- **Pages, components or directories in scope:**
- **Requested change:**
- **Files expected to remain untouched:**

Work only inside the stated scope. If the work requires a shared component or file outside it, stop and explain why before changing that file.

## What is already decided

These decisions are closed unless the human owner explicitly reopens them:

- 

## Locked facts

Use the exact approved wording or limits in the source of truth. Do not strengthen, generalise, update or reconcile factual claims without approval.

- 

## Approved assets

| Asset | Approved file | Intended use | Replacement allowed? |
| --- | --- | --- | --- |
|  |  |  | No |

## What must never change without approval

- approved facts, quotations and metrics
- names, roles, dates, locations and legal wording
- public URLs, domains, redirects and tracking IDs
- approved images, logos and downloadable files
- licence, provenance or copyright statements
- analytics, consent, form handling or third-party scripts
- deployment configuration or the production branch
- any settled design decision listed in the brief or decision log

Do not infer factual, legal, licensing or publication decisions.

## Advisory and legal-risk flagging

If the request touches privacy, employment or partner agreements, public claims, confidential information, accessibility obligations, copyright, licensing or regulated advice:

1. identify the issue plainly;
2. state what you can verify and what you cannot;
3. leave the decision to the human owner or appropriate professional;
4. do not publish while the issue is unresolved.

## Source-of-truth hierarchy

When sources disagree, use this order unless the human owner states otherwise:

1. explicit instruction for the current task
2. approved source-of-truth file
3. current project brief and decision log
4. approved design and content assets
5. existing implementation
6. comments, old drafts and inferred conventions

Report conflicts. Do not silently choose the most recent, most common or most confident version.

## Preview-first rule

- Work on a non-production branch.
- Record the current known-good commit or checkpoint before material work.
- Do not publish or merge unless explicitly instructed.
- Provide a real preview when the project supports one.
- Treat preview access as public unless it is protected and verified.

## QA requirements

- Run relevant automated checks.
- Review the actual page, not only the build output.
- Check desktop and mobile widths stated in the project brief.
- Verify facts, links, images, metadata, accessibility basics, overflow and console errors.
- Compare shared wording and treatment across pages when the change could create drift.
- Verify the live address after release.

If nothing is genuinely wrong, make no changes and report that.

## Observations vs edits

Do only the requested work. If you notice anything else that looks wrong, inconsistent, out of date or risky, report it without fixing it.

List observations separately from changes.

## Deployment permissions

- **May create a branch:** Yes / No
- **May create a preview:** Yes / No
- **May open a pull request:** Yes / No
- **May merge:** Yes / No
- **May deploy to production:** Yes / No
- **Does approval or merge trigger production automatically:** Yes / No / Unknown

If any publication permission is `No` or `Unknown`, do not publish.

## Reporting requirements

Return:

1. a short result summary;
2. changed files and why each changed;
3. checks run and their results;
4. preview or branch details;
5. observations not acted on;
6. unresolved decisions or risks;
7. rollback point;
8. whether anything reached production.
