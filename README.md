# Strapi UI Design - Claude Code Skill

[![GitHub release](https://img.shields.io/github/v/release/opkod-france/claude-skill-strapi-ui-design)](https://github.com/opkod-france/claude-skill-strapi-ui-design/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Strapi v5](https://img.shields.io/badge/Strapi-v5-2F2E8B)](https://strapi.io)
[![Claude Code](https://img.shields.io/badge/Claude_Code-Skill-D97706)](https://docs.anthropic.com/en/docs/claude-code)

A comprehensive Claude Code skill for creating production-grade Strapi v5 plugin admin interfaces using the Strapi Design System exclusively.

## Features

- **Strapi Design System v2** - Complete component reference (47 components)
- **UI Patterns** - Data tables, forms, modals, settings pages, dashboards
- **React Query Integration** - Proper data fetching with `useFetchClient`
- **Content Manager Integration** - Injection zones and context hooks
- **Accessibility** - WCAG-compliant, keyboard-navigable interfaces
- **Real Examples** - Complete plugin implementations ready to use

## Installation

### Option 1: Clone to Claude Skills Directory

```bash
git clone https://github.com/opkod-france/claude-skill-strapi-ui-design.git ~/.claude/skills/strapi-ui-design
```

### Option 2: Manual Installation

```bash
mkdir -p ~/.claude/skills/strapi-ui-design
cd ~/.claude/skills/strapi-ui-design
curl -O https://raw.githubusercontent.com/opkod-france/claude-skill-strapi-ui-design/main/SKILL.md
curl -O https://raw.githubusercontent.com/opkod-france/claude-skill-strapi-ui-design/main/patterns.md
curl -O https://raw.githubusercontent.com/opkod-france/claude-skill-strapi-ui-design/main/examples.md
```

### Option 3: Project-Level Installation

```bash
mkdir -p .claude/skills/strapi-ui-design
# Copy SKILL.md, patterns.md, examples.md to .claude/skills/strapi-ui-design/
```

## Usage

Once installed, invoke the skill in Claude Code:

```
/strapi-ui-design
```

Or Claude will automatically use it when building Strapi v5 plugin interfaces.

## Skill Contents

| File | Description |
|------|-------------|
| `SKILL.md` | Core skill definition with Design System components, import patterns, spacing system |
| `patterns.md` | Reusable UI patterns: tables, forms, modals, settings, state management |
| `examples.md` | Complete plugin implementations with routing, CRUD, dashboards |

## What You'll Build

### Admin Pages
- Plugin home pages with navigation
- Data management tables with sorting, filtering, pagination
- Settings pages with tabs
- Dashboard pages with statistics

### Components
- Forms with validation and Field API
- Modals and confirmation dialogs
- Empty states and loading states
- Error boundaries and API error handling

### Integration
- Content Manager injection zones
- React Query data fetching
- Strapi admin hooks (`useFetchClient`, `useNotification`)
- Plugin registration and routing

## Design Principles

This skill enforces **native Strapi experience**:

1. **Use only `@strapi/design-system`** - No custom styled-components
2. **Consistent spacing** - Use the 1-10 scale (multiply by 10 for px)
3. **Typography hierarchy** - alpha for titles, beta for sections, sigma for labels
4. **Accessible by default** - Field labels, aria-labels, keyboard navigation

## Example Topics

Ask Claude Code questions like:

- "Create a settings page for my plugin"
- "Build a data table with search and pagination"
- "Add a modal form for creating items"
- "Show me how to inject a panel in Content Manager"
- "Create a dashboard with statistics cards"

## Related Skills

- [strapi-plugin-dev](https://github.com/opkod-france/claude-skill-strapi-plugin-dev) - Backend plugin development
- [frontend-design](https://github.com/anthropics/claude-code/tree/main/skills/frontend-design) - General frontend interfaces

## Requirements

- Claude Code CLI
- Strapi v5.x project with `@strapi/design-system` v2

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

MIT License - see [LICENSE](LICENSE) for details.

## Acknowledgments

- [Strapi Design System](https://design-system.strapi.io/) - Official component library
- [Strapi Documentation](https://docs.strapi.io/) - Admin panel customization guides
- [Claude Code](https://claude.ai/code) - AI-powered coding assistant

## Author

Created by [Ayoub](https://github.com/ayhid)

---

**Note**: This skill is not officially affiliated with Strapi or Anthropic. It's a community resource for Claude Code users building Strapi admin interfaces.
