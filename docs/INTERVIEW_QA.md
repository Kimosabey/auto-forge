# Interview Q&A — AutoForge

### "Tell me about this project."
AutoForge is agentic CI/CD that plans, writes, and ships code through the software lifecycle. AutoForge takes an issue, plans the change with a LangGraph agent, generates code via AST-aware edits, and opens a PR that runs through CI — automating the routine parts of the engineering lifecycle.

### "What was the hardest part?"
Keeping an autonomous coding agent correct and reviewable rather than confidently wrong.

### "Why did you choose this stack?"
- **LangGraph** — stateful multi-agent orchestration.
- **OpenAI** — cloud llm reasoning.
- **Docker** — containerized local deployment.

### "How does it fit the rest of your portfolio?"
It follows my "" model — local logic/state/UI, cloud reasoning where it earns its cost — and shares the documentation and deployment conventions used across all my projects (AX-11).
