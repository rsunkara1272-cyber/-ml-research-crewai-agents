# -ml-research-crewai-agents
4 AI agents collaborating to research ML trends and write LinkedIn posts | Built with Claude
Multi-Agent AI System (CrewAI + Claude)
This project builds a team of AI agents that collaborate to discover, analyze, and produce insights from real machine learning research.
Instead of a single prompt, this system simulates a workflow of specialized roles, similar to a real team.
🧠 Agent Architecture
The system is composed of four agents:
🔵 Researcher
Scans and retrieves relevant machine learning research (2025 focus)
🟢 Analyst
Evaluates findings and selects the most impactful insight
🟠 Writer
Transforms the insight into a structured, human-readable post
🔴 Reviewer
Critiques and refines the output for clarity and quality
Each agent passes its output to the next → creating a fully automated pipeline.
🔄 Workflow
Research → Analysis → Writing → Review
No manual intervention required.
The agents collaborate autonomously to produce the final result.
📊 Example Output
The system surfaced research from Tufts University:
Neuro-symbolic AI achieved ~3x better performance
~100x lower energy usage
Training time reduced from ~36 hours to ~34 minutes
This entire insight was:
→ Discovered
→ Evaluated
→ Written
→ Refined
by the agent system.
⚙️ How It Works
Built using CrewAI for agent orchestration
Powered by Claude for reasoning and generation
Runs locally via a single script (main.py)
🚀 Run Locally
python main.py
Make sure you have:
Python installed
Required dependencies (CrewAI, API access configured)
💡 Why This Matters
This project demonstrates a shift from:
Using AI tools → Orchestrating AI systems
Instead of prompting a single model, we define:
Roles
Responsibilities
Workflow
This enables more structured, scalable AI applications.
