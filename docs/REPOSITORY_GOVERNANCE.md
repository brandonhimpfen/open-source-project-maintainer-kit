# Repository Governance Guide

This document provides a lightweight starting point for documenting how [PROJECT NAME] is maintained. Replace the placeholders and remove sections that do not fit the project.

## Project purpose

[PROJECT NAME] exists to `[STATE PROJECT PURPOSE]`.

The project's intended scope is `[DESCRIBE SCOPE]`.

## Roles

### Maintainers

Maintainers may review contributions, manage releases, organize project work, enforce project policies, and make repository-level decisions within their granted access.

Current maintainers: `[LIST OR LINK]`

### Contributors

Contributors propose or submit changes. Contribution does not automatically grant maintainer status or decision-making authority.

### Project lead or decision owner

If applicable: `[ROLE OR NAME]`

Remove this role if decisions are shared among maintainers.

## Decision-making

Routine decisions may be made through normal issue and pull-request review.

For significant changes, the project may seek input from maintainers and affected contributors before a decision. The decision process should prioritize project scope, technical quality, security, maintainability, compatibility, user impact, and available maintainer capacity.

Decision method: `[CONSENSUS / MAINTAINER VOTE / PROJECT LEAD / OTHER]`

Tie-breaking process: `[PROCESS OR NOT APPLICABLE]`

## Maintainer access

Repository permissions should be limited to the access reasonably needed for each role. Projects should periodically review privileged access and remove access that is no longer required.

Process for granting maintainer access: `[PROCESS]`

Process for removing or reducing access: `[PROCESS]`

## Releases

Release authority: `[ROLE OR PROCESS]`

Release cadence: `[CADENCE OR "AS NEEDED"]`

Release procedure: see `RELEASE_CHECKLIST.md` and any project-specific release documentation.

## Security

Security reports should follow `SECURITY.md`. Access to non-public vulnerability information should be limited to people who need it to investigate and respond.

## Conduct and moderation

Project-controlled spaces follow `CODE_OF_CONDUCT.md`. Moderation responsibilities are assigned to `[ROLE OR PROCESS]`.

## Inactive maintainers

A maintainer who is inactive for `[PERIOD]` may have privileged access reviewed. Removal of access is an operational security measure and does not erase prior contributions.

## Governance changes

Material changes to this governance document should be proposed through `[ISSUE / PULL REQUEST / OTHER PROCESS]` and recorded in repository history.

## Project continuity

Where practical, maintainers should document release credentials, critical infrastructure ownership, recovery procedures, and succession arrangements without placing secrets in the repository.
