# OpenPave Skills

Official catalog of skills and playbooks for [PAVE](https://github.com/cnrai/pave-dist). Every entry here is verified to work in the openpave sandbox. Each entry links to its own repository or gist.

## Skills & Playbooks

| `name` | Skill | Author | Category | Description |
|---|---|---|---|---|
| `dropbox-mcp` | [Dropbox MCP](https://github.com/cnrai/openpave-dropbox-mcp) | johnmak101-ops | Integrations | Operate Dropbox through the remote MCP server (`mcp.dropbox.com/mcp`) — verified doctrines for install, OAuth, and file operations. |
| `wrike-mcp` | [Wrike MCP](https://github.com/cnrai/openpave-wrike-mcp) | cnrai | Integrations | Operate Wrike through the remote MCP server (`mcp.wrike.com/v2`) — verified doctrines and workarounds for tasks, folders, and attachments. |
| `your-playbook` | [Example Playbook](https://gist.github.com/your-gist-id) | your-name | Playbook | *Template row — replace with your gist.* One line: what workflow this playbook teaches. |

Only entries verified against the hosted sandbox are listed. Legacy `pave install` marketplace skills are not included.

## Install a skill

Open a new chat and paste the link from the table above:

```
install https://github.com/cnrai/<the-skill-you-wanted>
```

PAVE registers the skill, then an installer session walks you through the setup steps. For example: `install https://github.com/cnrai/openpave-dropbox-mcp`

## Add a playbook

1. Write your playbook (an operational how-to, one topic per gist) and publish it as a [GitHub gist](https://gist.github.com).
2. Open a PR adding one row to the table:

```
| `my-slug` | [My Playbook](https://gist.github.com/you/gist-id) | your-name | Playbook | One-line description. |
```

## License

MIT
