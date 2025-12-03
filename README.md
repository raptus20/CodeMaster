# CodeMaster

AI-driven code analysis and improvement tool built on **AI-CORE principles**. Analyzes, suggests, and implements code improvements under human supervision.

## Overview

CodeMaster is a practical implementation of the [AI-CORE](https://github.com/raptus20/AI-CORE) framework's self-improvement philosophy applied to code quality and analysis.

It demonstrates how autonomous AI evolution works in a real-world domain (code analysis), with sandboxed execution, human-in-the-loop approval, and continuous learning from effective patterns.

## Features

- **Autonomous Code Analysis**: Analyzes code complexity, best practices, and quality metrics
- **AI-Powered Suggestions**: Uses AI models (DeepSeek/OpenAI/Claude API) to suggest improvements
- **Sandboxed Execution**: Tests all suggestions in isolated environments before implementation
- **Human Supervision**: All changes require explicit human approval before execution
- **Pattern Learning**: Learns from effective fixes and stores them as reusable patterns
- **Personal Style Adaptation**: Gradually adapts to each programmer's individual style
- **Fallback Mode**: Works without API keys using static analysis and built-in heuristics

## How It Works

1. **Analysis**: CodeMaster analyzes your code using static analysis and optional AI models
2. **Suggestions**: Generates improvement suggestions with explanations
3. **Sandbox Test**: Tests suggestions in isolated VM environments
4. **Approval**: Presents results for human review and approval
5. **Implementation**: Applies approved changes and logs the evolution

## Built on AI-CORE

CodeMaster is inspired by and built upon [AI-CORE](https://github.com/raptus20/AI-CORE), which provides:

- **Self-improvement framework**: Full-stack system for AI autonomous evolution
- **Sandboxed changes**: Safe testing environment for all modifications
- **Explicit memory**: Stores patterns and learns from successes/failures
- **Feedback loops**: Emotion-like signals that guide improvement direction
- **Human-in-the-loop**: User maintains control over all changes

For more details on the core framework, visit [AI-CORE repository](https://github.com/raptus20/AI-CORE).

## Quick Start

```bash
git clone https://github.com/raptus20/CodeMaster.git
cd CodeMaster
npm install

# Set environment variables (optional)
export DEEPSEEK_API_KEY=your_key_here

# Start analysis
npm start
```

## Configuration

- `API_KEY`: Optional - set to use external AI models
- `FALLBACK_MODE`: Enabled by default - static analysis always works
- `SANDBOX_TIMEOUT`: Timeout for sandboxed test execution (default: 5s)

## Philosophy

CodeMaster believes in:

- **Transparency**: Every suggestion is explainable
- **Human Control**: AI proposes, humans decide
- **Continuous Learning**: Improves over time from feedback
- **Open Source**: Built on open-source principles
- **Collaboration**: Works best with engaged developers

## Related Projects

- [AI-CORE](https://github.com/raptus20/AI-CORE) - The core self-improvement framework
- [CodeCraft](https://github.com/raptus20/CodeCraft) - Code learning framework
- [ORIAL](https://github.com/raptus20/ORIAL) - Custom programming language

## License

MIT - See LICENSE file for details

## Contributing

Contributions, feedback, and ideas are always welcome! Feel free to:

- Open issues with suggestions
- Submit pull requests with improvements
- Share your experiences and use cases
- Help improve the documentation

## Contact

For questions, feedback, or collaboration inquiries, feel free to reach out through:

- GitHub Issues
- GitHub Discussions
- Direct collaboration

---

**by [raptus20](https://github.com/raptus20) & contributors**
