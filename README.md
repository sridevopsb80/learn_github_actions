# learn_github_actions
To practice github actions

# Documentation

````
https://docs.github.com/en/actions/about-github-actions/understanding-github-actions
````
Workflows ar defined under .github/workflows

## To enable a workflow to be triggered manually

To enable a workflow to be triggered manually, you need to configure the workflow_dispatch event.

Documentation:
````
https://docs.github.com/en/actions/writing-workflows/choosing-when-your-workflow-runs/events-that-trigger-workflows#workflow_dispatch
````

## To run jobs in sequential order

By default, jobs will run in parallel, which is not desired while setting up a dev-qa-uat-prod structure. to run jobs sequentially, use job needs.
````
https://docs.github.com/en/actions/writing-workflows/choosing-what-your-workflow-does/using-jobs-in-a-workflow
https://docs.github.com/en/actions/writing-workflows/workflow-syntax-for-github-actions#jobsjob_idneeds
````
