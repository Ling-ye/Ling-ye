<h1 align="center">Lingye</h1>

## About Me

- **Game development**: Experienced with performance testing and analysis workflows used in
  game projects, from data collection and metrics to diagnostics and tooling.
- **Performance analysis**: Work with frame timings, CPU/GPU/FPS metrics, memory snapshots,
  and ADB data to compare trends, study correlations, and produce visual reports.
- **Agent development**: Explore agent patterns and modular combinations of tools, memory, RAG,
  MCP, and context engineering.
- **Automation**: Turn repetitive workflows into scripts, data pipelines, CLIs, desktop
  applications, and bots, with an emphasis on diagnostics and recoverability.

## Open Source

### [CC Port](https://github.com/Ling-ye/cc-port) · Public Beta

A local-first desktop resource manager for Codex, Claude Code, Cursor, Windsurf, and OpenCode. It
safely synchronizes Skills, MCP servers, Rules, Prompts, and Plugins through a private
Git repository controlled by the user.

- A shared Python core powers the desktop UI, CLI, and MCP server.
- Every write is planned before execution, with ownership tracking, target locks, backups,
  validation, and rollback.
- MCP credentials are replaced with placeholders before resources enter version control.
- The project ships as a Windows installer with environment diagnostics, CI, release notes, and
  user documentation.

### [Lingye_Agent](https://github.com/Ling-ye/Lingye_Agent) · Alpha

A modular Python agent framework for research and experimentation. Reasoning, tools,
memory, retrieval, and context management are designed as independently reusable components.

- Six agent patterns: Simple, Function Calling, ReAct, Plan-and-Solve, Reflection, and
  Context-Aware.
- Working, episodic, semantic, and perceptual memory, plus a RAG pipeline with query expansion,
  HyDE, and reranking.
- MCP tool integration, GSSC context engineering, and a unified interface for cloud and local
  OpenAI-compatible models.
- End-to-end examples for PDF learning, codebase maintenance, document generation, and search.

## Coming Next

### AgentStrata

A self-hosted, declarative platform for deploying, operating, and evaluating multi-channel AI
agents. It uses versioned `BotSpec` configurations to compose each agent while sharing contracts,
adapters, operations, and evaluation infrastructure.

- Per-instance selection of a native runtime, LangGraph, Codex, and other backends.
- Feishu and QQ / OneBot integrations with composable tools, MCP services, RAG, memory, and private
  wikis.
- Identity, role-based access, task isolation, credential boundaries, diagnostics, and logs.
- A React / FastAPI operations console, Linux / WSL deployment, and BFCL, GAIA, and IFEval
  evaluation support.

## Tools & Technologies

- **Agents**: LLM Agents · ReAct · Plan-and-Solve · Reflection · Function Calling · LangGraph ·
  RAG · MCP · ACP · Context Engineering
- **Applications**: Python 3.10+ · FastAPI · Pydantic · React · SSE · WebSocket ·
  Desktop GUI · CLI
- **Data & performance**: Qdrant · Neo4j · SQLite · pandas · NumPy · Matplotlib · OpenPyXL ·
  Unreal Insights · ADB
- **Engineering**: pytest · Ruff · mypy · Git · CI · Docker · systemd · Windows ·
  Linux / WSL
