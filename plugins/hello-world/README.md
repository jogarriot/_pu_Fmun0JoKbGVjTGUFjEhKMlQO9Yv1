# Hello World Plugin

A simple starter plugin to help you get started creating your own Claude Code plugins.

## What's Included

### Agents

- **helper** - A friendly helper agent that assists with general questions and provides guidance

### Commands

- `/hello` - Say hello and get a friendly greeting with helpful tips

## How to Use

1. Run `/hello` to get started with a friendly greeting
2. Ask the helper agent for assistance by saying "Can you help me with..."

## Customizing This Plugin

This plugin is meant to be a starting point. Feel free to:

1. **Modify the agent** - Edit `agents/helper.md` to change its personality or capabilities
2. **Add new commands** - Create new `.md` files in the `commands/` folder
3. **Add skills** - Create a `skills/` folder with `SKILL.md` files
4. **Add hooks** - Create a `hooks/` folder with `hooks.json`

## Creating Your Own Plugin

To create a new plugin:

1. Create a new folder in `plugins/` with your plugin name
2. Add a `plugin.json` with your plugin metadata
3. Add agents, commands, skills, or hooks as needed
4. Update the marketplace.json to include your new plugin
5. Install it with `claude plugin install my-plugin@Fmun0JoKbGVjTGUFjEhKMlQO9Yv1-marketplace`

## Resources

- [Claude Code Plugin Documentation](https://docs.anthropic.com/claude-code/plugins)
- [Example Plugins](https://github.com/anthropics/claude-code/tree/main/plugins)

