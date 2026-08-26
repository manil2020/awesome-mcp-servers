# Contributing

Thanks for helping expand this catalog! Here's how to add or update entries.

## Adding a new server

1. **Find the right category** in [README.md](README.md). If none fits, propose a new one in the PR description.
2. **Add a row** to the category table using this format:
   ```markdown
   | [Server Name](https://link-to-repo-or-docs) | One-line description ending with a period. |
   ```
3. **Keep entries alphabetical** within each category where practical.
4. **Descriptions** should be under ~100 characters. Focus on *what it does*, not marketing language.

## Quality bar

Before submitting, confirm the server:

- Has a working, public repository or official documentation page.
- Implements the [MCP specification](https://modelcontextprotocol.io/specification).
- Has been updated within the last ~12 months (or is otherwise clearly maintained).
- Is not a duplicate of an existing entry.

## Removing broken entries

If you spot a dead link, archived project, or abandoned server, open a PR removing it (or moving it to a new "Archived" section) with a note explaining why.

## PR checklist

- [ ] Entry added in alphabetical order within its category
- [ ] Link tested and working
- [ ] Description is concise and factual
- [ ] No duplicate entries
- [ ] Markdown table formatting preserved

## Reporting issues

Open a GitHub issue for:
- Miscategorized servers
- Missing well-known servers
- Broken links you don't have time to fix
- Suggestions for new categories

Thanks for contributing!
