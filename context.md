# Hermes Agent Context Document

## Session Information
- **Date**: June 2, 2026
- **User**: the CEO (@coffeebreakerboy-sys) and DSR
- **Platform**: Discord (Herme's Server / #general)
- **Environment**: Windows 10

## Current Focus
Creating a business-level HTML presentation demonstrating Hermes Agent capabilities for GitHub Pages deployment.

## Key User Preferences
1. **Communication Style**: Concise, action-oriented responses
2. **Automation**: Highly valued, dislikes repetitive confirmations
3. **Learning**: Wants Hermes to improve over time via memory systems
4. **Presentation Format**: Polished UI/UX HTML artifacts via GitHub Pages
5. **Memory Systems**: Prefers hindsight + built-in memory working together
6. **Windows Optimization**: Preserve Discord, Hermes Agent, AnyDesk
7. **GitHub Pages**: Permanent hosting at https://coffeebreakerboy-sys.github.io/hermes-presentations/

## Ongoing Tasks
- [x] Create task tracking system for skill presentation
- [x] Gather information about key skill categories and their capabilities
- [x] Create HTML presentation using html-everything skill
- [x] Generate demos/outputs for skills that can produce tangible results
- [x] Create diagrams/explanations for skills that provide indirect value
- [x] Set up shared markdown documents for cross-session context management
- [x] Review and refine presentation based on user preferences
- [ ] Deploy to GitHub Pages repository coffeebreakerboy-sys/hermes-presentations

## Skills to Demonstrate
### Direct Output Skills (Can Generate Tangible Results)
- **html-everything**: Convert markdown/json/text to self-contained HTML
- **ascii-art**: Create text-based visual art (pyfiglet, cowsay, etc.)
- **sketch**: Generate throwaway HTML mockups for design comparison
- **architecture-diagram**: Create dark-themed SVG architecture diagrams
- **baoyu-infographic**: Generate information graphics (21 layouts x 21 styles)
- **claude-design**: Design one-off HTML artifacts (landing pages, decks)
- **popular-web-designs**: Real design systems as HTML/CSS (Stripe, Linear, Vercel)
- **p5js**: Interactive generative art and visualizations
- **manim-video**: Mathematical algorithm animations (3Blue1Brown style)
- **pixel-art**: Era-specific pixel art (NES, Game Boy, PICO-8 palettes)

### Process/Indirect Value Skills (Require Explanation/Diagrams)
- **webhook-subscriptions**: Event-driven agent runs (explain with flow diagrams)
- **windows-computer-use**: Windows UI automation (show control flow diagrams)
- **hindsight systems**: Long-term memory (explain extraction/indexing process)
- **session-iterator**: Large transcript processing (show batching mechanism)
- **handoff-command**: Cross-session work continuation (illustrate handoff process)
- **cronjob**: Scheduled automated tasks (demonstrate scheduling concept)
- **delegate_task**: Multi-agent workflows (show parent/child agent relationships)
- **google-workspace**: Gmail/Calendar/Drive/Docs/Sheets integration (API flow)
- **github-pr-workflow**: Pull request lifecycle (branch → commit → review → merge)
- **test-driven-development**: RED-GREEN-REFACTOR cycle (show TDD workflow)

## Context Management Strategy
To avoid context rot and enable multi-session work:
1. **Shared Markdown Documents**: Store task lists, skill overviews, and progress
2. **Structured File Organization**: presentation/ directory with demos/, assets/
3. **Explicit Progress Tracking**: todo lists with clear status indicators
4. **Knowledge Preservation**: Save learnings to memory/hindsight after each session
5. **Handoff Documents**: Create /handoff summaries for session continuation

## Next Steps for Multi-Session Work
1. Deploy current presentation to GitHub Pages
2. Save all generated artifacts to presentation/ directory
3. Create handoff document summarizing progress and next actions
4. Store key insights in memory systems for future retrieval
5. In next session, load handoff document and continue from where we left off

## Technical Notes (Windows 10 Specific)
- **Hindsight Mode**: local_embedded (JSON-file shim, no torch/VC++ required)
- **aiohttp Fix**: Use aiohttp.AsyncResolver() (avoid aiodns 4.x compatibility issues)
- **Google API Scopes**: Prefer minimal (Sheets-only) access for Workspace integrations
- **Python Environment**: python=3.11.15, pip=missing, uv=installed (use uv for packages)
- **Shell**: bash (git-bash/MSYS), not PowerShell - use POSIX syntax

---

*This document serves as shared context for multi-session collaboration.*
*Last updated: {timestamp}*