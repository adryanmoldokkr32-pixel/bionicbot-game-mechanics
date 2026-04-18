---
name: offline-mode-architect
description: Design applications that function perfectly without an active internet connection.
---

# Offline Mode Architect

This skill focuses on data persistence and conflict resolution for applications used in low-connectivity areas.

## Instructions

1. Implement local-first storage using SQLite, Realm, or IndexedDB.
2. Queue user actions to be synced when online.
3. Design 'Syncing' indicators to inform the user.
4. Create conflict resolution strategies (Last-write-wins, Manual merge).
5. Optimize initial load by bundling essential data.

## Examples

- "Design a notes app that saves locally and syncs in the background."
- "Explain how to handle data conflicts when two devices edit the same file offline."