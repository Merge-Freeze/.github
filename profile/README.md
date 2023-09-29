The code freeze tool to stop merging and deployments
-------------------------------------------------------
test
Merge Freeze lets dev teams block or prevent the merging of pull requests, either during one-off situations or scheduled at certain times of the week.

**Note: Merge Freeze does not gain any access to your code.**

Install or learn more at:
* https://github.com/marketplace/merge-freeze
* https://mergefreeze.com

## Features
* **One-off freezes** - Anyone on your team can temporarily block merging into a branch of your choosing by clicking "Freeze"
* **Recurring freezes** - Create cron schedules in our UI so contributors can only merge during certain hours
* **HTTP API** - Get the current Merge Freeze status of a repository or trigger a freeze in 1 line of code with our API
* **Slack app** - Freeze pull requests to your protected branch with our simple `/mergefreeze` command. Unfreeze also supported!

**All features work without any access to your code.**

## Slack app (optional)

Our Slack plugin provides a `/mergefreeze` command that, when invoked, will show you the current status of your repository and a big shiny button to either freeze or unfreeze it.

It will also send your team a notification when someone implements a merge freeze,  which is a handy reminder that everyone should stop merging. You can configure which Slack channel these "stop pull request" notifications should go to.

## Mac menu bar (optional)

Our Mac menu plugin provides instant access to the status of all your project's repositories, sorted by frozen status and alphabetically. [Learn more](https://github.com/Merge-Freeze/mac-menu-plugin).
