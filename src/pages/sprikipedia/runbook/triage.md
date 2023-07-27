NOTE - this runbook is still up for discussion and needs final sign-off from team

# Daily backlog management responsibilities:
1. Ensure that all issues that you see on Slack, email, or otherwise are entered into github as issues (either by the original author, or by copy/pasting/creating new ones).
1. Look at all untriaged issues on the [project board](https://github.com/orgs/hackclub/projects/32).
1. Follow single-issue triage process below.

# Managing a single issue
1. If the issue conflates multiple issues into one issue, split the issue into its constituent parts by creating new issues (that would then be triaged following this same flow), and close the issue and stop here.
1. Ensure that the issue is properly labeled with one of the following labels:
    * **feature request** - add additional functionality
    * **bug** - problem with existing product
    * **tech debt** - Denotes an issue that was submitted by engineering relating to the health of the code of the project

1. Look at the contents of the issue and ensure that there is what appears to be sufficient detail explaining the issue (enough information that people could understand/work on it).  Reach out to the issue reporter for clarification if needed.  If a reasonable amount of information cannot be retrieved on an issue, close the issue with a comment and stop here.
1. Use your best judgment to assign a [complexity](#complexity) to the issue, airing on the conservative side.  If the complexity is low, add the “good first issue” label.
1. If this is a feature request, assign the issue to a member of the product team for approval and priority assignment.  If approval is denied, close the issue and stop here.
1. If this is a bug do your best to estimate the [priority](#priority) of the issue.  If it is not extremely obvious and requires a product opinion, assign the issue to the project lead for prioritization.
1. If this is a tech debt issue and the issue is not already prioritized, get feedback from engineering as to what its [priority](#priority) should be.
1. Change status field (or drag the issue in project view) to the Work Queue

# Definitions

### Complexity
* **Easy** ~one line of code/minor fixes
* **Medium** 4-8 hrs
* **Hard** > 8 hrs

### Priority
* **Low** - can easily live without this
* **Medium** - wishlist
* **High** - annoying; embarrassing
* **Blocker** - do or die
