# AgentPrompts

Production-ready prompt templates for building AI agents. Copy, customize, and deploy.

🔗 **[Live Demo](https://taylormade2k.github.io/agent-prompts/)**

## Overview

A curated library of battle-tested prompts specifically designed for AI agent development. No generic "write me an email" prompts here—just specialized templates for real agent architectures.

## Categories

| Category | Templates | Description |
|----------|-----------|-------------|
| **System Prompts** | 4 | ReAct agents, tool-calling, multi-agent orchestration |
| **Memory & Context** | 4 | Conversation summarization, entity extraction, memory consolidation |
| **Voice AI** | 3 | AI receptionists, objection handling, appointment scheduling |
| **RAG Patterns** | 3 | Query rewriting, chunk scoring, answer synthesis |
| **Business Automation** | 3 | Email classification, document parsing, meeting summaries |

## Features

- 📋 **One-click copy** to clipboard
- 🔍 **Search** across all templates
- 🏷️ **Filter** by category
- 📱 **Mobile-friendly** responsive design
- 🎯 **Variables highlighted** for easy customization
- 📖 **Usage guidance** for each template

## Usage

### Online
Visit the [live demo](https://taylormade2k.github.io/agent-prompts/) and browse templates.

### Local
```bash
git clone https://github.com/taylormade2k/agent-prompts.git
cd agent-prompts
# Open index.html in your browser
```

### Customization
Each template includes highlighted variables like `{{VARIABLE_NAME}}`. Replace these with your specific values:

```
# Before
You are the AI receptionist for {{COMPANY_NAME}}.

# After  
You are the AI receptionist for Acme Industries.
```

## Template Highlights

### ReAct Agent
The classic reasoning + acting pattern for complex multi-step tasks:
```
THOUGHT: [Reasoning]
ACTION: [Tool to use]
ACTION_INPUT: [Parameters]
OBSERVATION: [Results]
```

### Memory Consolidation
Transform episodic memories into semantic knowledge:
```
NEW_RULES:
- [Subject] [Predicate] [Object] (confidence: X%)
```

### AI Receptionist
Natural voice patterns optimized for phone calls:
```
- Use contractions (I'm, we're, you'll)
- Keep sentences short for clarity
- Mirror the caller's pace and energy
```

## Contributing

Have a battle-tested prompt template? Contributions welcome!

1. Fork the repository
2. Add your template to the `templates` array in `index.html`
3. Follow the existing format (id, title, category, description, variables, prompt)
4. Submit a pull request

## Related Projects

- [Agent Memory Service](https://github.com/taylormade2k/agent-memory-service) - Three-tier memory system for AI agents

## License

Apache 2.0 - See [LICENSE](LICENSE) for details.

## Author

**Conston Taylor**  
[TaylorMade Development Group](https://taylormadedev.com)  
[LinkedIn](https://linkedin.com/in/constontaylor)
