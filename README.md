# the-hour-legal

Public legal notices for **The Hour**.

Served via GitHub Pages at https://<your-username>.github.io/the-hour-legal/.

## Structure

- `index.md` — landing page, lists current + archived policies
- `privacy/v1.md` — v1.0 policy (offline app, no data collection)
- `privacy/index.md` — points to current policy version
- `_config.yml` — Jekyll/Pages config

## When shipping a new app version that changes data practices

1. Add `privacy/v2.md` (or vN) with the new policy. **Do not edit `v1.md`** — it's the permanent archived record.
2. Update `privacy/index.md` to link to the new version.
3. Add a link to the archived old version in the root `index.md`.
4. Commit and push. Pages rebuilds within ~1 minute.
5. Update the Play Console Data safety form to match.
