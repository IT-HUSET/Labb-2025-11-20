# Template CLAUDE.md - AI Coding Agent Rules, Operating Procedures, Guidelines and Core Project Memory

This file provides guidance to AI coding agents when working with code in this project.


---


_**TODO**: Add Project Overview, Architecture, Tech Stack, Structure etc. here._


---


## CRITICAL AND FOUNDATIONAL RULES
_Fully read and understand_ @docs/guidelines/CRITICAL-RULES-AND-GUARDRAILS.md


---


## Critical Development, UI/UX, and Architecture Guidelines and Standards
_Fully read and understand_ @docs/guidelines/DEVELOPMENT-ARCHITECTURE-GUIDELINES.md

See also: 
- _`docs/guidelines/UI-UX-GUIDELINES.md`_ when doing UX/UI related work
- _`docs/guidelines/WEB-DEV-GUIDELINES.md`_ when doing web development work


## Critical Documentation Resources
- [Add references to other important documentation files here]


---


## Useful Tools and MCP Servers

### Context7 MCP - Library and Framework Documentation Lookup (https://github.com/upstash/context7)
Context7 MCP pulls up-to-date, version-specific documentation and code examples straight from the source.

### Fetch (https://github.com/modelcontextprotocol/servers/tree/main/src/fetch)
A Model Context Protocol server that provides web content fetching capabilities

### Code Analysis and Style (Analysis, Linting and Formatting)

**Automatically use the IDE's built-in diagnostics tool to check for analysis, linting and type errors:**
- Run `mcp__ide_getDiagnostics` to check all files for diagnostics
- Fix any linting or type errors before considering the task complete
- Do this for any file you create or modify
