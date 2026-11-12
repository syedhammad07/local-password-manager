# Q&A Preparation

Questions the professor could ask, with a **short answer** first and then a **full answer** or **example from our project**.

[← Back to the report](../REPORT.md)

---

## Basics

**What is Agile?**
- **Short answer:** a way of working in short cycles with frequent feedback, so the team can adapt to change instead of following a fixed plan.
- **Our example:** the Parked section, the intake form, and status updates that flag risks early.

**What is Scrum?**
- **Short answer:** an agile framework with fixed-length sprints, a Sprint Goal, a Product Owner, a Scrum Master, a developer team, and four events (Sprint Planning, Daily Scrum, Sprint Review, Retrospective).
- **Our example:** the Password manager MVP project, with a Product Backlog, Sprint 1 - To Do and a Sprint Goal in the overview.

**Scrum vs Kanban?**
- **Scrum:** time-boxed sprints with a goal.
- **Kanban:** continuous flow with no sprints. You visualise the stages and limit work in progress.
- **Our example:** we use both. Scrum to build the product, Kanban for launch requests.

**What is a dependency? A milestone? A portfolio?**
- **Dependency:** a task that can't start or finish until another task is done. For example, Marketing can't write the launch email until Design hands over the assets.
- **Milestone:** a key checkpoint with no duration, like "v1.0 launch day" on 15 Jan 2027.
- **Portfolio:** a collection of related projects monitored together, like "Password Manager Launch 2027".

---

## Person 2: Automation

**Which Asana automation features provide the greatest value for agile teams, and what should teams consider before automating?**
- **Short answer:** forms, custom fields and rules together. Before automating, check that the process is stable, the input is reliable, humans keep the key decisions, and the rules get reviewed.
- **Full answer:** see the [Person 2 deep dive](person-2-workflow-automation.md#5-reflection).

**How does automation improve transparency and help evolve the workflow?**
- **Transparency:** every request goes through the same form and stages. R1 shows the owner instantly, R2 keeps the board correct, and the activity log records every action, including "Asana Rule".
- **Evolving the workflow:** because the board and dashboard are accurate, problems become visible. Our dashboard showed the approval bottleneck. In the retrospective we change the process or add a rule. That's inspect and adapt.

**What could go wrong with automation?**
- Wrong input gives wrong output.
- Notification noise.
- Hidden logic that new members don't see.
- Locking in an unstable process.
- **Our mitigation:**
  - required form fields;
  - Triage before In Progress;
  - reviewing the rules in each retrospective.

**Can automation reduce flexibility?**
- **Short answer:** yes, if every step is automated.
- **Our approach:** we automate only the admin (assigning, moving). Decisions such as approval and prioritisation stay human, and rules are easy to change.

**How would you identify a bottleneck?**
- **Short answer:** look for the stage where tasks pile up or stay too long.
- **Where to look:** the board columns or the dashboard chart of incomplete tasks by section.
- **Our case:** Review / Approval, with 3 waiting tasks.

**Why use a form instead of just creating tasks?**
- It forces the same structure every time.
- People outside the project can use it.
- It feeds the automation directly.

**Why a template?**
- Recurring work always starts with the same steps and Definition of Done.
- That means less setup, nothing forgotten, and consistent quality.

---

## Which Scrum events are best on Asana?

| Event | How well Asana fits |
|---|---|
| Sprint Planning | Best fit: backlog, moving stories into the sprint, owners and dates |
| Sprint Review | Best fit: status updates, dashboards, portfolio |
| Daily Scrum | Supported: everyone looks at the board, but the conversation is face to face |
| Retrospective | Weakest fit: there's no retro board, so we only record the actions |

**Why:** Asana is strong at planning and visibility, and weaker at the human conversation. It also has no burndown charts or story points, which Jira has.

---

## Practical scenarios

**A new stakeholder request arrives. What happens?**
1. The stakeholder submits the form.
2. R1 assigns the request and moves it to Triage.
3. The Product Owner checks its priority against the goal.
4. The request goes either to In Progress or to Parked.

**One department is delayed. What happens?**
1. The dependency shows which tasks are blocked.
2. The timeline shows the impact on the Go / No-Go decision and the launch milestone.
3. The status update is set to "At risk", and stakeholders see it in the portfolio.

**Conflicting priorities?**
- The Product Owner decides, using the goal as the tiebreaker: zero critical security findings beats nice-to-have features.

**How would you measure whether the process works?**
- Cycle time from request to Done.
- The number of tasks waiting in Review.
- Overdue tasks.
- Milestones completed on time.
- Whether we reach the goal: launch on 15 Jan and 500 users in 8 weeks.

---

## Critical thinking

**When is Asana not the best tool?**
- Deep software development (use Jira).
- Budgets and resource planning (use MS Project or Excel).
- Strict waterfall projects with a critical path.
- Formal risk registers.
- Very small one-off jobs.

**What if the team becomes too dependent on Asana?**
- Conversations move into comments and people stop talking.
- Asana should support the agile events, not replace them.
