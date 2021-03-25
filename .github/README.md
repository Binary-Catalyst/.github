# .github
[![CI](https://github.com/Binary-Catalyst/.github/actions/workflows/ci-sandbox.yml/badge.svg)](https://github.com/Binary-Catalyst/.github/actions/workflows/ci-sandbox.yml)

Organizational example template settings for CI

# TODOs
1. CODEOWNER file
2. Identify our Default labels (Should be prefixed by category and used sparingly to get attention.) Examples: 
  - effort-jiraComplexity
  - priority-jiraPriority
  - type-jiraIssueType
3. Auto-link for JIRA

## Actions
1. Release drafter
2. Auto Labeler
3. Pull request templates
4. https://github.com/marketplace/actions/super-linter
5. Create action for lighthouse audit: treosh/lighthouse-ci-action 
6. GT Metrix saved report and compared against performance budget
7. Setup jira-lint to integrate prs with Jira issues https://github.com/marketplace/actions/jira-lint 
8. Create PR automatically for virtually any step: peter-evans/create-pull-request 
9. Auto-generate PR Title based on branch name
10. Auto-generate body with ancillary info like issue type, issue description, staging link, production link, affects version, etc. (in JIRA)
11. Add action to auto apply labels based on pr title: TimonVS/pr-labeler-action 
