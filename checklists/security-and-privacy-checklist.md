# Security and Privacy Checklist

**This checklist is a first-pass review, not legal or security advice.** Use appropriate professional advice for the project, audience and jurisdictions involved.

## Access and credentials

- [ ] Only the people and services that need access have it.
- [ ] Credentials are not present in source files, prompts, screenshots, commits or downloadable files.
- [ ] Secrets use the hosting or deployment system’s protected storage.
- [ ] Old tokens, invitations and accounts have been reviewed.

## Production and previews

- [ ] The working branch cannot change production by accident.
- [ ] Everyone knows whether merge or approval triggers deployment.
- [ ] Preview access is treated as public unless protection is verified.
- [ ] Preview pages are not indexed and do not enter the sitemap where that matters.
- [ ] Preview activity does not contaminate production analytics.

## Data and claims

- [ ] Personal information is necessary, approved and handled appropriately.
- [ ] Confidential employer, partner or client information is absent.
- [ ] Public claims have an approved source and wording.
- [ ] Employment, partner or client agreements have been reviewed where publication could conflict with them.
- [ ] Downloadable files have been checked for hidden, private or outdated content and metadata.

## Assets and third parties

- [ ] Every image, logo, font, quotation and download has recorded licence or provenance.
- [ ] Third-party scripts are known, necessary and reviewed.
- [ ] Analytics and consent behaviour match the chosen implementation and applicable review.
- [ ] Forms collect only necessary information.
- [ ] Form destinations, retention, spam controls and failure behaviour are known.
- [ ] No legal, privacy or security decision has been inferred by the coding agent.
