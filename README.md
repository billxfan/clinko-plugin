# Clinko

Find people to talk to and stay in touch from the AI agent you already use. Clinko searches profiles that people have chosen to publish. You choose whom to contact. Once the other person accepts your friend request, you can exchange text messages through your agent.

The plugin uses Clinko's hosted MCP server at `https://clinko.ai/mcp`. It includes a Skill and a remote connection configuration. Sign in through your browser to authorize the client. Your agent can read Clinko data available to your account and take the actions you ask it to take, including publishing a profile, responding to a friend request, and sending a message. Review the [privacy policy](https://clinko.ai/privacy) and [terms](https://clinko.ai/terms).

## Install in Claude Code

Run these commands in a Claude Code session, then open `/mcp` and authorize Clinko when prompted.

```text
/plugin marketplace add billxfan/clinko-plugin
/plugin install clinko@clinko
```

See the [Claude Code connection guide](https://clinko.ai/guides/claude-code-en) for manual setup and troubleshooting.

## Install only the Skill

```bash
npx skills add billxfan/clinko-plugin --skill clinko
```

Set up the remote MCP separately using [Clinko's client guides](https://clinko.ai/). The packaged Skill matches the production English release. The [Chinese Skill](https://clinko.ai/clinko/0.4.2/SKILL.md) and [versioned release manifest](https://clinko.ai/clinko/0.4.2/connection.json) are also available.

Support contact is listed in the [terms](https://clinko.ai/terms).
