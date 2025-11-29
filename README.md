# Personal Marketplace

This is your personal Claude Code marketplace where you can create and manage your own plugins.

## Pre-installed Plugins

### hello-world
A simple starter plugin to help you get started. Includes:
- **helper** agent - A friendly assistant for general questions
- `/hello` command - Get a greeting with helpful tips

Try it out: Run `/hello` or ask "Can you help me?"

## Structure

```
plugins/                          # /space/{userId}/plugins
├── .claude-plugin/
│   └── marketplace.json          # Marketplace configuration
├── plugins/
│   └── hello-world/              # Pre-installed starter plugin
│       ├── plugin.json
│       ├── agents/
│       │   └── helper.md
│       ├── commands/
│       │   └── hello.md
│       └── README.md
└── README.md
```

## Creating Your Own Plugin

1. Create a new folder in `plugins/` with your plugin name
2. Add a `plugin.json` with your plugin metadata:
   ```json
   {
     "name": "my-plugin",
     "version": "1.0.0",
     "description": "My awesome plugin"
   }
   ```
3. Add agents, commands, skills, or hooks as needed
4. Update `.claude-plugin/marketplace.json` to include your plugin
5. Install it using your marketplace type:
   - Private: `claude plugin install my-plugin@private-Fmun0JoKbGVjTGUFjEhKMlQO9Yv1-marketplace`
   - Public: `claude plugin install my-plugin@public-Fmun0JoKbGVjTGUFjEhKMlQO9Yv1-marketplace`

## Plugin Components

- **agents/** - Specialized AI agents (`.md` files)
- **commands/** - Slash commands (`.md` files)  
- **skills/** - Skills with `SKILL.md` files
- **hooks/** - Event hooks with `hooks.json`

## Resources

- [Claude Code Docs](https://docs.anthropic.com/claude-code)
- [Plugin Examples](https://github.com/anthropics/claude-code/tree/main/plugins)

## Tips

- Changes to your plugins are tracked in Git (visible in Git Viewer)
- Edit `plugins/hello-world/` to customize the starter plugin
- Use the helper agent as a template for creating your own agents
