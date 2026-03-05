# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- **Receptor** - The webhook receiver workflow (not "receiver" or "gateway")
- **Procesador** - The AI processor workflow (not "processor" or "handler")
- **Agente** - AI agent (use Spanish term in technical contexts)
- **Buffer** - Message grouping system in Redis
- **Confirmación** - Order confirmation (use "confirmo" or "confirma" for trigger word)

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

- Document all implemented features accurately (Orders, General Inquiries are COMPLETE)
- Clearly mark partially implemented features (Table Reservations, Venue Reservations are NOT FUNCTIONAL)
- Don't document internal Azure server details or credentials
- Focus on n8n workflow configuration and deployment, not restaurant operations
