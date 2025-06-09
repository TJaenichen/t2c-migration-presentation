# T2C Migration Presentation

## Overview
This is a reveal.js presentation about the T2C (TSQL to C#) Migration project, demonstrating how LLMs are used to migrate stored procedures at scale.

## Project Structure
- `index.html` - Main presentation file with all slides
- `genconvo.txt` - Full migration prompt example (embedded in HTML)
- `transformer-architecture.png` - Transformer architecture diagram
- `package.json` - Project dependencies (reveal.js)

## Key Topics Covered
1. The Challenge - 20+ years of business logic in 1500+ stored procedures
2. LLM Evolution - Context windows from GPT-1 (512) to Claude 4.7 (2M+)
3. Migration Pipeline - Automated workflow with feedback loops
4. One-shot Prompting - Complete context approach for accuracy
5. Test Generation - Automated test creation from SQL logic
6. Claude Code Automation - Hands-off execution with human-in-the-loop

## Running the Presentation
```bash
# Install dependencies
npm install

# Start local server
npm start
# or
npm run serve
```

Then open http://localhost:8080 in your browser.

## Navigation
- Use arrow keys to navigate between slides
- Press ESC to see all slides
- Press S for speaker notes (if available)

## Technical Details
- Built with reveal.js
- Self-contained HTML with embedded prompt content
- No external dependencies needed for viewing
- Includes interactive SVG diagrams and syntax-highlighted code examples

## Deployment
The presentation is completely self-contained in `index.html` and can be:
- Opened directly in a browser (file://)
- Served from any web server
- Shared as a single HTML file (with accompanying PNG image)