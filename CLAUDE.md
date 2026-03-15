# LOJA Studio - Claude Instructions

## Memory System

At the **start of every session**, read these memory files to restore context:

- `memory/decisions.md` - Key decisions made across sessions
- `memory/people.md` - People, collaborators, suppliers
- `memory/preferences.md` - Julien's working preferences and standards
- `memory/user.md` - Context about Julien and LOJA Studio

At the **end of every session** (or when significant new information emerges), update the relevant memory files with anything worth remembering:

- New decisions or changed directions -> `decisions.md`
- New people or updated roles -> `people.md`
- Learned preferences or workflow habits -> `preferences.md`
- Updated context about Julien or LOJA -> `user.md`

## Guidelines

- Keep memory files concise and organized by section
- Remove outdated information rather than letting it accumulate
- Only store confirmed, stable information - not guesses or temporary context
- When in doubt about what to remember, ask Julien
