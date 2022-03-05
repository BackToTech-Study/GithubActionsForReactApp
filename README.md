# GithubActionsForReactApp
Automated test execution and integration for a react app

## Define a [workflow](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [x] Create the [workflow](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#workflows)
- [x] Define trigger [event](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)
- [x] `pull_request` event will not trigger if there is a merge conflict

## Define unit test action
- [x] name your action. Optional there is a [marketplace](https://github.com/marketplace?type=actions) already defined actions
- [x] select a [runner](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#runners) execution environment
- [x] define script steps
- [x] use an external action
- [x] define a working directory
- [x] execute multiple commands in sequence

## Define cypress test action
- [ ] Define secrets to use
- [ ] Clone the external repository
- [ ] Execute cypress test cases

## [Protected branches](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches)
- [ ] [Require status checks before merge](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-status-checks-before-merging) 
- [ ] [Require review before merge](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-pull-request-reviews-before-merging)
- [ ] [Require resolved conversations before merge](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-conversation-resolution-before-merging)
- [ ] [Enable auto-merge](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/automatically-merging-a-pull-request#enabling-auto-merge)

## Deploy to netlify
