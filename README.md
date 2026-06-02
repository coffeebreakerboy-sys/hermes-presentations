# Hermes Agent Skills Presentation

This directory contains a business-level HTML presentation showcasing Hermes Agent capabilities, along with supporting materials for multi-session work and context management.

## Contents

### Core Presentation
- `Hermes_Agent_Capabilities_Presentation.html` - Main HTML presentation created with html-everything skill

### Demonstrations & Outputs
- `/demos/ascii_banner.txt` - ASCII art demonstration
- `/demos/dashboard_mockup.html` - HTML mockup/dashboard demonstration

### Context Management Files
- `context.md` - Shared context document for multi-session work
- `tasks.md` - Task tracking with progress indicators
- `skills_overview.md` - Detailed breakdown of skill categories and capabilities
- `indirect_value_skills.md` - Explanation of skills that provide value through processes rather than direct output

### Explanatory Diagrams
- `/diagrams/webhook_flow.txt` - Webhook subscriptions workflow
- `/diagrams/cron_scheduling.txt` - Cron job scheduling explanation
- `/diagrams/delegate_task.txt` - Multi-agent delegation system
- `/diagrams/hindsight_memory.txt` - Hindsight memory system operation
- `/diagrams/session_iterator.txt` - Processing large transcripts
- `/diagrams/handoff_workflow.txt` - Cross-session handoff process

## How to Use for Multi-Session Work

### 1. Starting a Session
At the beginning of each session, load the context:
```
# Read the shared context document
read_file presentation/context.md

# Check current task status
todo  # or read presentation/tasks.md
```

### 2. Tracking Progress
Update your progress in the task list:
```
# Example: Mark a task as completed
todo --todos '[{"id": "task3", "content": "Create HTML presentation using html-everything skill", "status": "completed"}]' --merge true
```

### 3. Ending a Session
Before ending your session:
1. Update all task progress in `tasks.md`
2. Add any new discoveries or decisions to `context.md`
3. Create a handoff document if needed: `/handoff [description of where to resume]`
4. Save any generated artifacts to appropriate directories

### 4. Resuming Work
When returning to continue work:
1. Load the handoff document (if created) or `context.md`
2. Check `tasks.md` for pending/in_progress items
3. Continue from where you left off

## Presentation Features

### Direct Output Skills Demonstrated
- **html-everything**: This presentation itself
- **ascii-art**: Text-based visual banners and decorations
- **sketch**: HTML mockups for UI/UX design
- **architecture-diagram**: System and infrastructure diagrams

### Indirect Value Skills Explained
Through diagrams and explanations in `/diagrams/` and `indirect_value_skills.md`:
- **webhook-subscriptions**: Event-driven automation
- **cronjob**: Scheduled task execution
- **delegate_task**: Multi-agent parallel processing
- **hindsight systems**: Long-term memory and learning
- **session-iterator**: Large transcript processing
- **handoff-command**: Cross-session work continuation

## Technical Notes (Windows 10 Specific)

- **Hindsight Mode**: local_embedded (JSON-file shim, no torch/VC++ required)
- **Memory Systems**: Both Hindsight and built-in memory active
- **File Organization**: All presentation assets contained in this directory
- **Context Preservation**: Shared markdown documents prevent context rot
- **Preferred Tools**: Uses html-everything for lightweight, self-contained HTML output

## Next Steps for Enhancement

1. Add interactive demonstrations using skills like:
   - `comfyui` for AI-generated images
   - `manim-video` for mathematical animations
   - `p5js` for interactive visualizations
   - `baoyu-infographic` for data visualization

2. Create specialized presentations for:
   - Development workflow assistance
   - Research and analysis capabilities
   - Automation and system control
   - Creative content generation

3. Enhance context management with:
   - Automated backup of presentation assets
   - Version control for markdown documents
   - Integration with handoff system for automatic context saving

---

*Presentation created: June 2, 2026*
*Last updated: See git history or file timestamps*
*Context preserved across sessions via shared markdown documents*