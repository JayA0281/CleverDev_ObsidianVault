https://linearb.io/
```table-of-contents
```
## What does it do?
it is a software engineering intelligence platform

**It tracks** what developers do (commits, PRs, cycles, deployments) and....
**turns it** into metrics, sooo....
**companies can:**
- improve delivery speed
- identify bottlenecks
- enforce engineering standards

### Product capabilities
#### 1. Engineering metrics
- Cycle time: time from the first commit to deployment on production
- PR size & review time: PR size is the number of lines added, deleted or modified, keeping PR size below 200 lines is optimal for high quality changes
- deployment frequency
- lead time
#### 2. Workflow visibility
- where PRs are getting stuck
- who is overloaded/ where are the bottlenecks
#### 3. Automation(WorkerB + gitStream)
##### gitStream (the decision-making engine)
it is the decision engine that standardizes engineering behavior
1. **What is it?** 
	it is a rule bsed automation engine that watches Git activity and reacts in real time
2. What does it monitor from your repos?
	- PR size
	- Files changed
	- Who opened PR
	- Labels/branches
	- Test coverage signals
	- Review status
3. How does it work(flow)?
	1. Developer opens a PR
	2. gitStream evaluates rules
	3. It decides what should happen
	4. triggers action
4. Types of rues you can define
	1. Routing rules
		- Auto-assign reviewers based on:
			- File ownership
			- Expertise
			- Workload
	2. Quality Rules
		- Block or flag PRs:
			- too large
			- missing tests
			- risky files touched
	3. Workflow rules
		- Add labels
		- Move PRs across stages
		- Trigger notifications
	4. Prioritization rules
		- Critical fixes -> faster review path
		- Low priority -> deprioritize
##### WorkerB(the execution + communication layer)
1. What it is
	a bot that lives in slack + git and interacts with developers
2. What it does
	- Sends nudges
	- Posts comments on PRs
	- Reminds reviewers
	- Alerts about issues
3. where does it show up
	- GitHub/GitLab comments
	- Slack messages
	- Notifications
### Strengths
- it doesnt only show dashboards, It suggets improvements and automates workflows.
- Workflow visibility
- Bottleneck identification

### Weaknesses
- They measure activity, but more activity doesnt always mean more impact, as a result, complex work may get undervalued
- its hard to map their metrics to real business impact

#### Integrations
- **AI tools:** Codex, Firebase studio, Gemini CLI, Claude, etc
- **Project Tracking:** Azure boards, Jira and Shortcut
- **Code Management:** Azure Repos, Bitbucket, GitHub, GitLab 
- **CI/CD:** Circle CI, Jenkins
- **Communication:** Microsoft Teams, Slack,
- **Security and Quality:** Jazzberry, Jit, Meticulous, etc

### Basic structure of LinearB
#### **Layer 1:** Visibility
- Metrics
- Dashboards
- Reports
#### **Layer 2:** Action
- Automation(WorkerB, gitStream)
- Alerts and nudges
#### **Layer 3:** Optimization
- AI insights
- DevEx improvements
- forecasting & planning

Features:
- MCP server
- DevEx Surveys
- DevEx Reporting
- Cost Optimization(shows roi of engineering invistments)
- Measuring AI Impact
- AI Developer Support
- Code Review Lifecycle
- Dev Team Managemet

## Marketing campaigns that LinearB has
### [Dev Interrupted](https://devinterrupted.substack.com/)
A community for engineers by linearB