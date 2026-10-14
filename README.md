# n8n-sprint2-issue-triage
https://github.com/donoftime2018/n8n-sprint2-issue-triage 

Week 6 public test repository for an n8n GitHub Issue Triage workflow 

The week 6 Sprint 2 n8n GitHub Ledger Issues workflow was designed to record the necessary information about any new issues made to this repository. This information includes, but is not limited to, the issue title and url, the type or route of issue based on the title, and the reporter of the issue. The issue logged to both the github_issue_ledger and github_issue_route_log. 
 
The issue was logged to github_issue_ledger after determining it's route. The route came from the title of the issue, which was formatted such as *Bug: blank screen after logout*, where the route is before the colons, in this case *bug*. After logging the issue in *github_issue_ledger*, the workflow then proceeds to determine if the issue is an intentional failure test or not. If so, then the issue is logged as such in *github_issue_ledger*. Otherwise, the current issue is logged in *github_issue_route_log*, and is logged as recorded in *github_issue_ledger*.
