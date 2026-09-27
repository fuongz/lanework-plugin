# Lanework plugin for Claude Code

The [Lanework](https://lanework.dev) board inside Claude Code: its MCP tools,
and a checkpoint on your card after every turn so another agent can pick the
work up.

```
/plugin marketplace add fuongz/lanework-plugin
/plugin install lanework@lanework
```

Then, once: `/mcp` to sign the MCP server in, and `! lanework login` to sign
this machine in for the hook. Details in
[`plugins/lanework/README.md`](plugins/lanework/README.md).

This repository is **published from Lanework's source**; changes made here
directly are overwritten on the next release. `bin/lanework-checkpoint.cjs`
is a build output.
