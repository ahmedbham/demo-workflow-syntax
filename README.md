# :rocket: Workflow syntax

Demo repository for basic GitHub Actions workflow syntax.

:exclamation: **This is a template repository**
  - Please click ***Use this template*** to clone the repo into your user account or a different organization that you own, and run the demo from there
  - If you're unable to use your personal account or a different organization, feel free to use this one. Just make sure to complete the **Cleanup** steps afterwards :house_with_garden:

## Usage 

### Creating a workflow

1. Click on the **Actions** tab
1. If there are already existing workflows, click **New workflow** to navigate to the Starter workflow overview
1. Select the **Simple workflow** 
1. Walk through the syntax (events, jobs, runner, steps, ...)
1. Give the workflow a distinct file name and workflow `name` 
1. Commit the workflow into a new branch and create the PR

### Workflow logs and other features

1. Observe the PR view which should show the workflow triggering (as long as the `pull_request` event was not removed from the workflow)
1. Show the **Checks** tab inside the PR, which should show the workflow log
1. Once the workflow has completed, merge the PR and delete the branch
1. Click on the **Actions** tab and click on the current workflow run
1. Show the features and information available in the workflow run GUI
    - Visualization, re-running workflows, downloading logs, searching, toggling time stamps, etc.
    - In the log, expand the **Set up job** --> **Virtual environment**, and navigate to the **Included software** link to show the VM spec of the runner
1. Show how to trigger the workflow manually (available as long as the `workflow_dispatch` event was not removed from the workflow)
1. Show how to disable the workflow

### :house_with_garden: Cleanup

1. If the workflow was run in this repository, perform the following steps:
    - Ensure PRs are closed/merged
    - Ensure any new branches are deleted
    - Delete the workflow and commit to the main branch

