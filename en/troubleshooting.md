---
title: "Troubleshooting"
lang: en
---

# Troubleshooting

**The comparison is slow or seems frozen.**
It runs in the background. Very large files can take time; cancel with **⌘.** and try smaller files or enable the line filters.

**I can't connect over SSH.**
1. Check **host, port, username**, and credentials.
2. For **key** auth, only **Ed25519/ECDSA** are supported; for **RSA-only** servers, switch to **password**.
3. Credentials live in the **Keychain**; if the server password changed, update the saved connection.

**The Apple Intelligence button/panel is disabled or missing.**
Confirm you're on **macOS 26 (Tahoe) or later** on an **Apple Silicon** Mac and that **Apple Intelligence** is **enabled** in System Settings. If Apple Intelligence isn't available, these features are hidden (the rest of the app keeps working).

**`git difftool` doesn't open Uranium Diff.**
Reinstall the helper from **"Merge ▸ Git integration…"** and make sure `uraniumdiff` is on your **PATH**. That screen also has the manual Terminal commands.

**The app can't open a folder or file.**
Uranium Diff runs in the macOS **sandbox** and only accesses what you authorize. Re-select (authorize) the folder or file from within the app.

**I see garbled characters ("mojibake").**
The file is likely not **UTF-8** (encoding not yet supported).

**Downloading from a URL fails.**
The URL must be **HTTP/HTTPS** and publicly reachable; there's a **50 MB** limit.

**My 14-day trial ended.**
The app keeps working on the **Free plan**. To restore Pro features, subscribe from the Uranium Diff Pro screen.

**Still stuck?**
Reach out: [Support & bug reports](support.md).
