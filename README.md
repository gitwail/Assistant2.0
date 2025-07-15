# Assistant2.0

| Path                            | Description                                                   |
|---------------------------------|---------------------------------------------------------------|
| `Agent2.O/src/agents/`          |                                                               |
| ├── `__init__.py`               | Registers each agent graph with the LangGraph server          |
| ├── `scheduler_agent.py`        | LangGraph graph → MCP “calendar” tool: finds free-time blocks |
| ├── `finance_agent.py`          | LangGraph graph → MCP “bank-feeds” tool: spending & budget insights |
| ├── `habit_agent.py`            | LangGraph graph → MCP “reflection” tool: daily review & habit plan |
| └── `supervisor.py`             | LangGraph router: dispatches user queries to the right agent graph |

# Domains

| Domain             | Agent Name        | Example Tasks                                                 |
| ------------------ | ----------------- | ------------------------------------------------------------- |
| Time/Schedule      | `scheduler_agent` | Manage calendar, book/reschedule, find free time              |
| Finances           | `finance_agent`   | Track expenses, budgeting, financial planning                 |
| Social Life        | `social_agent`    | Reminders for birthdays, suggest meetups, relationship health |
| Habits & Health    | `habit_agent`     | Daily tracking, mood logging, exercise goals                  |
| Knowledge/Learning | `learning_agent`  | Plan reading goals, summarize materials, spaced repetition    |
| Supervisor         | `supervisor`      | Route tasks to the right agent, refine queries, delegate      |
