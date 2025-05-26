<!-- PR Title Should match format:
#{TicketNumber}: Description of Changes

if no ticket number, use `chore:`, `fix:`, `feat:` etc.

Example:
#123: Add pagination to List Applications endpoint
-->

## Summary

<!-- High level, short description of work done. 1-2 sentences. -->

## Issues
- #(issue number)
- #(issue number)

## Description of Changes
<!-- Describe the changes in your pull request **per service or package**, providing enough context for reviewers.

Be sure to call out any breaking changes, as well as any special instructions required to run the new code (i.e. New or updated dependencies? `pnpm i`. New migrations to run? `pnpm run migrate-dev`. etc.) 

Add a heading for each app/package that you have contributed changes to and list the changes included.
-->

<!-- EXAMPLE START
General description of the changes in your PR and the functionality it adds.

### UI
- Added a new component `ComponentName` which achieves some functionality.
  - Description of `ComponentName` and the changes you made to create it
  - Added package [`package name`](https://link.to/package) to handle something

### Server
- Added new endpoint `GET /stuff`that does stuff


### Special Instructions
Before running these changes, you will need to ...

-->

## Readiness Checklist

- [ ] **Self Review**
  - I have performed a self review of code
  - I have run the application locally and manually tested the feature
  - I have checked all updates to correct typos and misspellings
- [ ] **Formatting**
  - Code follows the project style guide
  - Autmated code formatters (ie. Prettier) have been run
- [ ] **Local Testing**
  - Successfully built all packages locally
  - Successfully ran all test suites, all unit and integration tests pass
- [ ] **Updated Tests**
  - Unit and integration tests have been added that describe the bug that was fixed or the features that were added
- [ ] Documentation
  - All new environment variables added to `.env.schema` file and documented in the README
  - All changes to server HTTP endpoints have open-api documentation
  - All new functions exported from their module have TSDoc comment documentation
