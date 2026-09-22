# Rollback Checklist

- [ ] Stop making further edits. Do not try several fixes on top of an uncertain state.
- [ ] Identify the last known-good branch, commit, checkpoint or deployment.
- [ ] Inspect the diff between the known-good state and the failed release.
- [ ] Confirm that restoring the checkpoint will not discard unrelated approved work.
- [ ] Restore the known-good state using the project’s documented procedure.
- [ ] Rebuild the restored version.
- [ ] Test the affected page, shared components and critical actions before redeploying.
- [ ] Redeploy the restored version.
- [ ] Verify the real live address in a fresh session on desktop and mobile.
- [ ] Confirm the failed change is no longer public.
- [ ] Record what was restored, who did it and when.
- [ ] Document the cause before trying the failed change again.
