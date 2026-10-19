# everything-whiteboard (Vibeclones mirror)

Hosted builds of the **whiteboard** app from Puter's [Everything](https://github.com/HeyPuter/everything) project (MIT). The code is theirs; this repo only builds and hosts it. Puter's own site serves only the newest version; this repo keeps older snapshots so the timeline can be explored in a browser.

- Latest: `/everything-whiteboard/latest/`
- A specific snapshot: `/everything-whiteboard/v<snapshot>/`
- Snapshot list: `/everything-whiteboard/versions.json`

Upstream doesn't publish releases or version numbers, so each snapshot is named after the date and short hash of an upstream commit that touched `src/whiteboard`, for example `v2026.10.16-ab12cd3`. These are not official releases. A scheduled workflow builds a new snapshot when that app changes upstream; older ones are built on request.
