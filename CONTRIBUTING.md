# Contributing to content-creation-skill

Thank you for helping improve this Claude Code skill. Here's how to contribute effectively.

## How to Contribute

### Reporting Issues
- **Bugs**: Use the [Bug Report](.github/ISSUE_TEMPLATE/bug-report.md) template
- **Platform updates**: Use the [Platform Update](.github/ISSUE_TEMPLATE/platform-update.md) template — platforms change constantly, and keeping character limits, algorithm tips, and formatting rules current is one of the most valuable contributions

### Submitting Changes
1. Fork the repository
2. Create a feature branch (`git checkout -b update/linkedin-character-limits`)
3. Make your changes
4. Test with Claude Code to verify the skill works as expected
5. Submit a pull request using the [PR template](.github/pull_request_template.md)

## What We're Looking For

### High-Value Contributions
- **Platform updates**: Character limit changes, new content formats, algorithm shifts
- **New content types**: Emerging formats (e.g., new social platforms, interactive content)
- **Template improvements**: Better structures based on real-world testing
- **SEO updates**: Search engine algorithm changes that affect content strategy
- **Repurposing workflows**: New or improved multi-platform distribution strategies
- **Tone/voice guidance**: Better frameworks for maintaining brand consistency

### Writing Style
- Be concise and actionable — every sentence should help Claude produce better content
- Use specific numbers over vague advice ("150–160 chars" not "keep it short")
- Include examples where they clarify the instruction
- Structure with headers, bullet points, and tables for scannability
- Write for Claude as the reader — clear instructions it can follow precisely

### What to Avoid
- Marketing fluff or filler content
- Unverified platform specs (always include a source date or link)
- Duplicate coverage of topics already well-handled elsewhere in the skill
- Removing existing content without a clear reason and replacement

## File Structure

| File | Purpose |
|---|---|
| `SKILL.md` | Core skill instructions — the main file Claude reads |
| `references/platforms.md` | Platform-specific rules and limits |
| `references/templates.md` | Content templates for common formats |
| `references/repurposing.md` | Repurposing workflows |
| `references/seo-content.md` | SEO writing guidelines |

## Testing Your Changes

The best way to test is to install the skill in Claude Code and run through common content creation tasks:

1. Copy the updated skill to `~/.claude/skills/content-creation/`
2. Start a Claude Code session
3. Ask Claude to create different content types (blog post, LinkedIn post, email sequence)
4. Verify the output follows your updated guidelines

## Code of Conduct

Be respectful, constructive, and focused on making the skill better. We welcome contributors of all experience levels.
