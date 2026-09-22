# Rollback Plan

Fill this in before a material release. The purpose is to make recovery a known procedure rather than a decision made while something is broken.

## Current known-good state

- **What is working now:**
- **Last verified at:**
- **Verified by:**

## Branch

- **Working branch:**
- **Production branch:**

## Commit or checkpoint

- **Known-good commit/checkpoint:**
- **How to identify it:**
- **Where it is stored:**

## Files likely to change

- 

## Rollback trigger

Restore the known-good state if any of these occurs:

- 

## Restore procedure

Write the exact project-specific steps in plain language.

1. Stop further edits and releases.
2. Confirm the failed release and the known-good checkpoint.
3. Restore the checkpoint using the approved repository or hosting procedure:
   - 
4. Rebuild or redeploy the restored version:
   - 
5. Record who performed the rollback and when.

## Live verification after rollback

- [ ] Open the real public address in a fresh browser session.
- [ ] Confirm the failed change is absent.
- [ ] Check the affected page or action on desktop and mobile.
- [ ] Check navigation, forms and other shared components touched by the release.
- [ ] Confirm analytics and consent behaviour if they were in scope.
- [ ] Record the live version or commit now serving.
