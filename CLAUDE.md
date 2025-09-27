# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Mintlify Documentation

### Working relationship
- You can push back on ideas—this can lead to better documentation. Cite sources and explain your reasoning when you do so
- ALWAYS ask for clarification rather than making assumptions
- NEVER lie, guess, or make up information

### Project context
- Format: MDX files with YAML frontmatter
- Config: docs.json for navigation, theme, settings
- Components: Mintlify components

### Commands
```bash
# Install Mintlify CLI
npm i -g mint

# Run local development server
mint dev

# Update Mintlify CLI to latest version
mint update
```

### Content strategy
- Document just enough for user success - not too much, not too little
- Prioritize accuracy and usability of information
- Make content evergreen when possible
- Search for existing information before adding new content. Avoid duplication unless it is done for a strategic reason
- Check existing patterns for consistency
- Start by making the smallest reasonable changes

### Frontmatter requirements for pages
- title: Clear, descriptive page title
- description: Concise summary for SEO/navigation

### Writing standards
- Second-person voice ("you")
- Prerequisites at start of procedural content
- Test all code examples before publishing
- Match style and formatting of existing pages
- Include both basic and advanced use cases
- Language tags on all code blocks
- Alt text on all images
- Relative paths for internal links

### Git workflow
- NEVER use --no-verify when committing
- Ask how to handle uncommitted changes before starting
- Create a new branch when no clear branch exists for changes
- Commit frequently throughout development
- NEVER skip or disable pre-commit hooks

### Project structure
The documentation is organized into:
- **Guides tab**: Getting started, customization, writing content, and AI tools sections
- **API reference tab**: API documentation and endpoint examples
- **Configuration**: docs.json manages navigation structure, theme colors, logo settings, and navbar configuration
- **Content files**: MDX format with frontmatter for metadata

### Do not
- Skip frontmatter on any MDX file
- Use absolute URLs for internal links
- Include untested code examples
- Make assumptions - always ask for clarification