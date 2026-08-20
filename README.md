# boxingtest-discord-invite

Public host for BlitzBoxing Discord invite JSON + Actions. **Not** the Boxing game repo. Do **not** copy into `Boxing/.github/`.

Repo: https://github.com/realamex/boxingtest-discord-invite

| File | Role |
|------|------|
| `discord-invite.json` | Client GET (raw) |
| `.github/workflows/check-discord-invites.yml` | Daily UTC 06:00 + `workflow_dispatch`; User-Agent `BlitzBoxing-InviteCheck/1.0` |

Invite codes (aligned with game SO):

- setting `VwQW2ht9vp`
- lose `dPJjgE46hX`
- win `Y8AMQJVEtK`

Client `remoteJsonUrl` (raw, B-06b):

`https://raw.githubusercontent.com/realamex/boxingtest-discord-invite/main/discord-invite.json`

After first push: enable Actions; Watch failure mail for the GitHub user who created this workflow.
