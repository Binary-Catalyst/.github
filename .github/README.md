# .github

[![CI](https://github.com/Binary-Catalyst/.github/actions/workflows/ci-sandbox.yml/badge.svg)](https://github.com/Binary-Catalyst/.github/actions/workflows/ci-sandbox.yml)

Organizational example template settings for CI

## TODOs

1. CODEOWNER file
2. Identify our Default labels (Should be prefixed by category and used sparingly to get attention.) Examples:

     - effort-jiraComplexity
     - priority-jiraPriority
     - type-jiraIssueType IE: story, maintenance, bug, research, hotfix

3. Auto-link for JIRA

## Actions

1. Release drafter or [Create
   Release](https://github.com/actions/create-release) (DONE)
2. Auto Labeler
3. Pull request templates
4. [super-linter](https://github.com/marketplace/actions/super-linter)
5. Create action for lighthouse audit: treosh/lighthouse-ci-action
6. GT-Metrix saved report and compared against performance budget
7. Setup [jira-lint](https://github.com/marketplace/actions/jira-lint) to integrate prs with Jira issues
8. Create PR automatically for virtually any step: [peter-evans/create-pull-request](https://github.com/peter-evans/create-pull-request)
9. Auto-generate PR Title based on branch name
10. Auto-generate body with ancillary info like issue type, issue description, staging link, production link, affects version, etc. (in JIRA)
11. Add action to auto apply labels based on pr title: [TimonVS/pr-labeler-action](https://github.com/TimonVS/pr-labeler-action)
