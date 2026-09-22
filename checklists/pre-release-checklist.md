# Pre-Release Checklist

Do this against the release candidate, not an earlier preview.

## Scope and preview

- [ ] Review the final changed-file list and actual diff.
- [ ] Confirm every change belongs to the approved request.
- [ ] Review the final preview as a real page.
- [ ] Check the relevant pages on desktop and mobile.
- [ ] Know whether approval or merge will automatically deploy to production.

## Content and experience

- [ ] Facts match the source of truth.
- [ ] Claims do not exceed their evidence.
- [ ] Names, dates, metrics and quotations are correct.
- [ ] Internal and external links reach the intended destination.
- [ ] Images are the approved files, load correctly and crop well.
- [ ] Basic accessibility checks pass: headings, labels, alt text, keyboard use, focus and contrast.
- [ ] No console errors relevant to the change remain.
- [ ] No overflow, clipping, overlap or unexpected horizontal scroll appears.

## Discovery and measurement

- [ ] Page titles and descriptions are correct.
- [ ] Canonical, robots and sitemap behaviour are intentional.
- [ ] Social preview title, description and image have been checked.
- [ ] Consent behaviour works in a fresh session and does not hide the page.
- [ ] Analytics fires only as intended and uses the correct production ID.

## Release and recovery

- [ ] The current production state has a named rollback point.
- [ ] The restore procedure is understood.
- [ ] The release owner has approved publication.
- [ ] The production release is started deliberately.
- [ ] After release, run a live smoke test at the real public address.
- [ ] Record the commit or version serving in production.
