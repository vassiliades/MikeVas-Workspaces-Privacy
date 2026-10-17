---
title: MikeVas Workspaces Privacy Policy
---

# MikeVas Workspaces Privacy Policy

**Effective date: October 17, 2026**

MikeVas Workspaces is a local-first browser extension for saving, organizing and restoring browser workspaces. This policy includes the manual synchronization and recovery features in version 4.0.0.

## Data handled by the extension

To provide its workspace features, the extension handles the following information from tabs selected by the user:

- page titles and URLs;
- tab order and pinned state;
- browser tab group names, colors, order, and collapsed state;
- workspace names, colors, settings and local revision information.

This information is used only to create, display, update, synchronize, and restore the user's browser workspaces.

## Storage and synchronization

Workspace information and preferences are stored locally in the user's browser profile. Version 4.0.0 also stores per-workspace synchronization baselines, identity mappings, browser-specific exclusions and pending-operation recovery journals locally. Recovery journals may contain before/after and shared-file workspace snapshots to prevent unsafe repetition of uncertain operations.

File synchronization is optional and requires a separately installed Sync Helper, the user's native-messaging permission and a user-selected `workspaces.json` file. In version 4.0.0, **Check changes** reads the file for comparison without applying changes. The user chooses actions per workspace and reviews **Apply** and a separate confirmation before selected changes are written to the shared file or this browser's saved copy. Skipped changes remain pending. Supported conflict merges are shown for review rather than selected silently. Earlier versions may label manual synchronization **Sync now**.

Recovery inspection reads current state. A supported, explicitly confirmed recovery unlock clears only the local pending journal without writing the shared file. Other uncertain outcomes remain blocked for inspection.

The extension does not automatically synchronize on installation or startup. The developer does not operate a server receiving workspace information, and the extension does not send workspace information or telemetry to the developer.

The selected file can be in a OneDrive or other cloud-synchronized folder. A separately configured storage provider may upload that file, including its page URLs and titles, under the user's account and that provider's terms. This transfer is controlled by the user's file-sync configuration, not a developer-operated backend. Native helpers are installed separately; they are not downloaded executable extension code.

## Data sharing and sale

MikeVas Workspaces does not sell user data. It does not use or transfer user data for advertising, creditworthiness, lending, or purposes unrelated to its workspace-management purpose. Workspace information is not sent to the developer. Optional native-helper and user-configured cloud-file handling are described above.

## Website content

The extension does not inspect or collect the body content of web pages. It handles the title and URL shown by the browser only as needed to save and restore selected tabs.

It does not request access to the browser's history database or bookmarks. Saved tab titles and URLs are nevertheless browsing-related data handled for the workspace feature. Explicitly opening a workspace loads its saved sites normally, and those sites receive ordinary browser requests. No saved sites open automatically on installation or startup.

## Data retention and deletion

Saved workspace information remains in the browser profile until removed by the user, extension storage is cleared, the browser profile is removed or the extension is uninstalled. Local synchronization and recovery records can include workspace snapshots and are retained as needed for comparison, pending actions and safe recovery. Deleting a saved workspace should not be assumed to erase every pending journal or previous snapshot immediately.

An explicitly confirmed browser-specific exclusion removes that browser's saved copy, not the shared workspace or open tabs. Shared files, separate backups and any copies retained by a cloud provider remain under the user's control and that provider's retention rules; uninstalling the extension does not delete them. Preserve unsynchronized edits and inspect pending operations before clearing browser storage or uninstalling. A shared-file backup does not include browser-only unsynchronized edits or local pending journals.

## Limited Use

The use of information received from browser APIs complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.

## Changes

Material changes to this policy will be published on this page with a revised effective date.

## Contact

Privacy or support questions can be submitted through the publisher contact information shown in the browser extension store listing.
