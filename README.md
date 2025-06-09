# T2C Migration Presentation

A reveal.js presentation about the T2C (TSQL to C#) Migration project, demonstrating how Large Language Models are used to migrate stored procedures at scale.

## 🌐 Live Presentation

**View the presentation online:** https://tjaenichen.github.io/t2c-migration-presentation/

![Presentation QR Code](presentationpageqr.png)

## 📋 Overview

This presentation covers the journey of migrating over 1500 stored procedures from TSQL to C# using modern LLMs like Claude and GPT-4. It explores the evolution of context windows, migration pipelines, and practical techniques for large-scale code migration.

## 📖 Topics Covered

1. **The Challenge** - 20+ years of business logic in 1500+ stored procedures
2. **LLM Evolution** - Context windows from GPT-1 (512 tokens) to Claude 4.7 (2M+ tokens)
3. **Migration Pipeline** - Automated workflow with feedback loops
4. **One-shot Prompting** - Complete context approach for accuracy
5. **Test Generation** - Automated test creation from SQL logic
6. **Claude Code Automation** - Hands-off execution with human-in-the-loop
7. **Tips & Tricks** - Practical learnings from the migration process

## 🚀 Running Locally

The presentation uses CDN dependencies and is completely self-contained. You can:

1. **Open directly in browser:**
   ```bash
   # Simply open index.html in your browser
   open index.html
   ```

2. **Serve with a local server:**
   ```bash
   # Using Python
   python -m http.server 8080
   
   # Using Node.js (if you have npm installed)
   npm start
   ```

## 🎮 Navigation

- **Arrow keys** - Navigate between slides
- **ESC** - Overview of all slides
- **S** - Speaker notes (if available)
- **F** - Fullscreen mode

## 🛠 Technical Details

- Built with [reveal.js](https://revealjs.com/)
- Pacific Dev branding with teal gradient theme
- Interactive SVG diagrams and syntax-highlighted code examples
- Embedded full migration prompt (1400+ lines)
- Self-contained HTML with CDN dependencies

## 📂 Project Structure

```
├── index.html                    # Main presentation file
├── repoqr.png                   # QR code for this repository
├── presentationpageqr.png       # QR code for live presentation
├── transformer-architecture.png # Transformer diagram
├── genconvo.txt                 # Full migration prompt example
├── CLAUDE.md                    # Claude Code documentation
└── README.md                    # This file
```

## 🔗 Repository

**GitHub Repository:** https://github.com/TJaenichen/t2c-migration-presentation

![Repository QR Code](repoqr.png)

## 📚 Resources

- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)
- [Anthropic Prompt Engineering](https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering)
- [Claude Code Getting Started](https://docs.anthropic.com/en/docs/claude-code)
- [Bond Capital - The AI Report](https://www.bondcap.com/reports/tai)

## 📄 License

This presentation is provided as-is for educational and reference purposes.

---

*Generated with [Claude Code](https://claude.ai/code)*