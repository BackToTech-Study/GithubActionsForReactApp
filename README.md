# Github Actions For React App
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
- [ ] For pulling private a repo setup a [deployment key](https://docs.github.com/en/developers/overview/managing-deploy-keys#deploy-keys). This allows you to use credentials for a single repository rather than your personal access token which exposes all your repositories.
- [x] Protecting [secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets) needed in github actions
- [x] [Clone the external repository](https://github.com/actions/checkout#checkout-multiple-repos-side-by-side)
- [x] Execute cypress test cases


## Deploy to netlify
- [ ] 


# Merge pull request conditions and automations

## [Protected branches](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches)
- [x] [Require status checks before merge](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-status-checks-before-merging) 
- [x] [Require review before merge](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-pull-request-reviews-before-merging)
- [x] [Require resolved conversations before merge](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-conversation-resolution-before-merging)
- [x] [Enable auto-merge](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/incorporating-changes-from-a-pull-request/automatically-merging-a-pull-request#enabling-auto-merge)
