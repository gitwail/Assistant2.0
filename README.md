# Assistant2.0

Agent2.O/
└── src/
    └── agents/
        ├── __init__.py            # registers each agent graph with the LangGraph server
        ├── scheduler_agent.py     # LangGraph graph → MCP “calendar” tool: finds free‑time blocks
        ├── finance_agent.py       # LangGraph graph → MCP “bank‑feeds” tool: spending & budget insights
        ├── habit_agent.py         # LangGraph graph → MCP “reflection” tool: daily review & habit plan
        └── supervisor.py          # LangGraph router: dispatches user queries to the right agent graph
