# prnouncer-config

This repository contains some GitHub Action Workflows for [prnouncer](https://github.com/guardian/actions-prnouncer).

## Why?
It's useful to have a robot remind you what PRs are awaiting review, 
rather than making the contributor feel guilty about reminding you!

## How?
1. Create a webhook in your Chat channel
  - append `&threadKey={threadKey}` to the Webhook URL to get threading
2. Add the webhook as a secret to this repository. All Engineering Managers have admin access to this repo.
3. Create a Workflow file in [./github/workflows](.github/workflows)
4. Merge and wait for the robot to wake up
