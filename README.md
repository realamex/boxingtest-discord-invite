# Invite JSON

This repo hosts one public JSON file: [`discord-invite.json`](./discord-invite.json).  
That file is the source of truth for the three invite links. Do not copy the URLs into this README.

## Fields

| Key | Meaning |
|-----|---------|
| `setting` | Invite opened from settings |
| `lose` | Invite opened after a defeat |
| `win` | Invite opened after a victory |

Each value must be a full `https://` invite URL. Unknown keys are ignored.

## Raw URL (for the client)

GitHub’s file page (`…/blob/…`) is HTML, not JSON. The client must GET the **raw** file:

1. Open [`discord-invite.json`](./discord-invite.json) on GitHub.
2. Click **Raw**.
3. Copy the address bar (`raw.githubusercontent.com/…`). That URL is what belongs in the client config.

Do not use the `blob` page URL as the fetch address.

If you changed the workflow action script, don't forget rerun it and delete old running workflow!
