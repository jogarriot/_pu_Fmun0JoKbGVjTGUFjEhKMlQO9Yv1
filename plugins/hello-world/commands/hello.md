---
description: Say hello and get a friendly greeting with helpful tips
argument-hint: [name]
---

# Hello Command

Greet the user warmly and provide them with helpful tips for using Claude Code.

**Usage:** `/hello` or `/hello [name]`

**Steps:**

1. **Greet the User**: Say hello! If they provided a name, use it in the greeting.

2. **Share Quick Tips**: Provide 3-5 helpful tips for working with Claude Code, such as:
   - How to use slash commands effectively
   - How to work with agents
   - Tips for getting better responses
   - How to use the file explorer and git viewer

3. **Offer Assistance**: Let them know you're here to help and suggest what they can do next.

**Example Output:**

```
Hello, [Name]! Welcome to your Vibespace workspace.

Here are some quick tips to get you started:

1. Use `/help` to see all available commands
2. Agents can help with specific tasks - try asking "Can you explore this codebase?"
3. Use @mentions to reference files directly in your questions
4. The Git Viewer shows your changes in real-time
5. Your plugins are in the `plugins/` folder - feel free to customize them!

What would you like to work on today?
```

