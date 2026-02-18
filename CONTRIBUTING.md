# Contributing to Strapi UI Design Skill

Thank you for your interest in contributing to the Strapi UI Design skill for Claude Code!

## How to Contribute

### Reporting Issues

- Use GitHub Issues to report bugs or suggest features
- Include clear descriptions and examples where possible
- Check existing issues before creating a new one

### Submitting Changes

1. **Fork the repository**
   ```bash
   git clone https://github.com/opkod-france/claude-skill-strapi-ui-design.git
   cd claude-skill-strapi-ui-design
   ```

2. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Follow the existing code style and formatting
   - Test your changes with Claude Code if possible

4. **Commit your changes**
   ```bash
   git commit -m "Add: description of your changes"
   ```

5. **Push and create a Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```

## File Structure

| File | Purpose | When to Edit |
|------|---------|--------------|
| `SKILL.md` | Core skill definition | Adding Design System components, import patterns |
| `patterns.md` | Reusable UI patterns | Adding component patterns, state management |
| `examples.md` | Complete implementations | Adding real-world plugin interfaces |

## Content Guidelines

### Adding New Patterns

When adding to `patterns.md`:

1. Use clear section headers with `##`
2. Include complete TypeScript/TSX code examples
3. Explain when and why to use the pattern
4. Use only `@strapi/design-system` components

### Adding New Examples

When adding to `examples.md`:

1. Provide complete, runnable code
2. Include file paths as comments (e.g., `// admin/src/pages/MyPage.tsx`)
3. Add a summary table of key patterns demonstrated
4. Ensure code follows Strapi v5 admin conventions

### Code Style

- Use TypeScript for all code examples
- Use proper indentation (2 spaces)
- Include type annotations
- Use root imports from `@strapi/design-system`
- Follow Strapi Design System conventions:
  - Typography variants: alpha, beta, delta, sigma, pi
  - Spacing scale: 1-10 (multiply by 10 for px)
  - Colors via props, not custom values

### Component Patterns

Always demonstrate:
- Proper Field.Root usage for forms
- React Query for data fetching
- useNotification for feedback
- Accessibility attributes (aria-label, etc.)

## What We're Looking For

### High Priority

- New Strapi Design System v2 patterns
- Accessibility improvements
- Content Manager integration examples
- Complex form patterns
- Dashboard and analytics UI

### Nice to Have

- Dark mode considerations
- RTL language support patterns
- Performance optimization tips
- Animation and transition examples

## Design System Resources

When contributing, reference:
- [Strapi Design System Storybook](https://design-system.strapi.io/)
- [Strapi Admin Panel Docs](https://docs.strapi.io/dev-docs/admin-panel-customization)
- [@strapi/design-system source](https://github.com/strapi/design-system)

## Questions?

Feel free to open an issue for any questions about contributing.

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
