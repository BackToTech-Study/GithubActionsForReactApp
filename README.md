# GithubActionsForReactApp
Automated test execution and integration for a react app

## Define a unit test [workflow](https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions)
- [x] Create the [workflow](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#workflows)
- [x] Define trigger [event](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows)
- [x] `pull_request` event will not trigger if there is a merge conflict
- [x] name your action. Optional there is a [marketplace](https://github.com/marketplace?type=actions) already defined actions
- [x] select a [runner](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions#runners) execution environment
- [x] define script steps
- [x] use an external action
- [x] define a working directory
- [x] execute multiple commands in sequence

## Define a cypress test workflow
- [ ] Define secrets to use
- [ ] Clone the external repository
- [ ] Execute cypress test cases

## Define a automatic merge workflow
- [ ] Trigger workflow on review submittest [pull_request_review](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#pull_request_review) trigger
- [ ] Trigger workflow on completion of [check_suite](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#check_suite)
- [ ] Add job [conditions](https://docs.github.com/en/actions/learn-github-actions/expressions)
- [ ] Checking the [review state](https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows#running-a-workflow-when-a-pull-request-is-approved)
- [ ] Checking the status of the [pull request checks](https://docs.github.com/en/rest/guides/getting-started-with-the-checks-api)

## Deploy to netlify
