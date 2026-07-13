---
layout: default
title: "Quick start"
lang: en
ref: quick-start
permalink: /en/quick-start/
---

# Quick start

### 1. Each comparison lives in its own tab
Use the tab-bar buttons to create **file**, **folder**, or **Git branch** sessions. Close each with its ✕.

### 2. Pick the two sides
In an empty session, choose the **left** and **right** file from your Mac, from a **URL**, or from an **SSH server**. You can also **drag files from Finder** — drop two at once and they auto-fill left and right. Use the center button to swap sides.

### 3. Compare
Press **"Compare now"** (or Return). The computation runs in the background; cancel large ones with **⌘.**

### 4. Explore the differences
- Switch between **Side-by-side**, **Inline**, and **Tree** (for JSON/YAML/XML/plist) with the toolbar selector.
- Jump between changes with **▲/▼** or **⌘↑ / ⌘↓**.
- The **minimap** on the right summarizes the whole file (green = added, red = deleted, yellow = modified); click to jump.
- The colored buttons show/hide added, deleted, or modified lines.

### Compare folders
Create a **folder** session and pick two local or remote (SSH) folders. Results are grouped into **added, deleted, modified, and identical**. **Double-click** a modified file to open its detailed diff in a new tab. You can copy files between sides with a conflict policy (replace / keep both / cancel).

### Compare Git branches
With **"Merge ▸ Compare Git branches…" (⇧⌘B)**, pick a local repository and two branches or commits. You'll see the changed-file list with stats and can open each file's detail.

### Use Uranium Diff as a Git tool
In **"Merge ▸ Git integration…"**, install the `uraniumdiff` helper and register the app as a `difftool`/`mergetool`. Automatic setup asks to authorize your home folder once; the same screen shows the manual Terminal commands. Then run `git difftool` in any repo and diffs open as Uranium Diff tabs.

### Apple Intelligence
The **"AI"** toolbar button opens a panel that can summarize the diff and explain the focused change. All processing happens on your Mac. *Always verify the generated information.*

### Export results
In a comparison's **"More" (…)** menu, copy the unified diff to the clipboard or export the result as **HTML** or **PDF**, preserving colors and statistics.

### Keyboard shortcuts
| Shortcut | Action |
|---|---|
| ⌘N | New file session |
| ⌘O | Open left file |
| ⇧⌘O | Open right file |
| ⌘W | Close active session |
| ⇧⌘B | Compare Git branches |
| ⌘↑ | Previous change |
| ⌘↓ | Next change |
| ⌘+ / ⌘− | Increase / decrease font size |
| ⌘. | Cancel the running comparison |
| ⌘C | Copy selection |
| ⌘? | Open in-app help |
