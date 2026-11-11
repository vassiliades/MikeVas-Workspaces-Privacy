---
title: MikeVas Workspaces Privacy Policy
---

# MikeVas Workspaces Privacy Policy

**Effective date: November 10, 2026**

MikeVas Workspaces saves, organizes and restores user-selected browser Workspaces. The common MikeVas Connect runtime owns authorized shared-file access; a separate legacy Sync helper is not required by the current distribution.

## Workspace data and synchronization

The add-on handles selected page URLs/titles, tab order/pinned state, group names/colors/order/collapse state, workspace names/settings and local revision metadata. This content is stored in the browser profile. Local sync baselines, identity mappings, exclusions and pending-operation recovery journals can contain before/after and shared-file snapshots needed to resolve uncertain operations.

File synchronization uses the shared file explicitly chosen through Connect. Check changes and Review actions show proposed changes; Apply requires confirmation. Automatic review is not permission for automatic writes. Opening a saved Workspace loads its pages; installation/startup does not open them automatically. Local file validation/write success does not prove cloud-provider upload or receipt by another device.

Users control the file location and any external cloud/share service. Those services handle workspace content under their own policies. Shared-file backups exclude browser-only unsynchronized edits and may exclude local pending journals. Uninstalling an add-on does not remove shared files, provider copies or backups. Inspect pending operations and preserve unsynchronized edits before clearing local storage. Existing locks are not removed merely because they are old.

## Connect presence and optional diagnostic delivery

The local Connect native channel receives fixed product/browser states, an opaque profile identifier and the version/build identity loaded by the add-on. A connected native channel is not proof of successful authentication, routing or synchronization. Browser/device labels and fixed connection/build summaries can be included in the configured organization server's device view.

Diagnostic delivery is optional and configured in Connect Settings → Tunnels with **Send diagnostic metadata to the server** and **Save diagnostic delivery**. It uses the configured HTTPS server and the same protected OS-user device token; it is not an advertising or developer analytics service. Fixed event categories, results, timings, build/state metadata and device/browser labels may be delivered. Passwords, MFA codes, vault field values, workspace contents and page response bodies are excluded from this diagnostic schema. Acknowledged Connect event history is retained for four days; pending events remain until acknowledged, within a bounded 16 MiB journal. Server event history is retained for 90 days. Diagnostic uploads require the optional logs:write device-token scope; an existing policy-only token does not gain that permission automatically. Local histories, pending delivery and server retention are separate. Turning delivery off does not erase already delivered history. Review exported diagnostics before sharing; exports or workspace recovery data may contain information beyond fixed delivery events.

Use Activity and Settings → Tunnels to inspect pending/delivered/rejected counters and delivery errors. Delivered is retained local history, not a lifetime total. Do not post tokens, private hosts, unsanitized exports or personal data in public support issues. Public GitHub Help pages generate normal website requests handled by GitHub; no product credentials are added to Help links.

## User control and contact

Users can review/apply individual changes, choose another shared file, disable automatic review/optional diagnostics, export or delete local Workspaces, stop Connect and uninstall. Review exports because they contain URLs/titles and workspace content. Contact the publisher through the extension store listing for privacy/support questions. Material policy changes are published here with a revised effective date.
