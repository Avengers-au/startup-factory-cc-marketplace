# claude-skills-marketplace

Registry of Claude Code skill plugins. Analogous to [obra/superpowers-marketplace](https://github.com/obra/superpowers-marketplace).

## Registered plugins

| Plugin | Description |
|--------|-------------|
| `claude-skills` | Centralized Claude Code skills library |

## Usage

```
claude plugin marketplace add Avengers-au/claude-skills-marketplace
claude plugin install claude-skills@claude-skills-marketplace
```

## Adding a plugin

Add an entry to `.claude-plugin/marketplace.json`:

```json
{
  "name": "your-plugin-name",
  "source": "azhao/your-plugin-repo",
  "description": "What it does",
  "version": "1.0.0"
}
```
