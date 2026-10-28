# Fork notes (vrgfa)

Fork of [eexpress/gs-clock](https://github.com/eexpress/gs-clock).

## Branches

| Branch | Purpose |
|---|---|
| `main` | Upstream, untouched (= version 20 on extensions.gnome.org, GNOME ≤44 format). |
| `gnome-45-port` | **What is installed** (`~/.local/share/gnome-shell/extensions/cairo@eexpss.gmail.com` is a symlink to this clone — keep this branch checked out). Port to the GNOME 45+ extension format. |

## Local changes log

- (before 2026-10-28) — Port to GNOME 45+: ES module imports instead of `imports.gi` / `imports.cairo`, `St.DrawingArea` instead of the removed `Clutter.Canvas`, exported classes, `metadata.json` as installed.
- 2026-10-28 — Put into git on `gnome-45-port`. The extension is currently not enabled.
