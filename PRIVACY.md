# MockupMirror Privacy Policy

**Effective date: July 18, 2026**

MockupMirror is a Figma plugin that creates image snapshots ("Mirrors") of frames and components inside your Figma file. This document describes exactly what data the plugin collects, why, and what it never touches.

## What never leaves your device

All design content is processed locally inside Figma:

- Exported PNG images are written directly into your Figma file. They are never uploaded anywhere.
- Layer names, page names, file names, and any other canvas content are never transmitted.
- Text you type into the plugin (such as the Mirror name prefix) is stored only in Figma's local plugin storage and is never transmitted.

The plugin's network access is restricted by its manifest to a single domain, `api-js.mixpanel.com`. Figma enforces this restriction at the platform level, so the plugin is technically unable to send data anywhere else.

## What we collect

We use [Mixpanel](https://mixpanel.com) to understand how MockupMirror is used and to support users who report problems. The following is the complete list of what is sent:

1. **A random identifier** — a UUID generated locally on your device. It is not derived from your Figma account and cannot be traced back to it.
2. **Your Figma display name and avatar URL** — collected so that when you report an issue (for example, in a Community comment), we can look up what happened in your sessions and help you. This is the only personally identifiable information we collect.
3. **Usage events** — which features are used and how often: counts of Mirrors created or synced, counts of Mirror source types (e.g. how many frames vs. components), whether each plugin setting is on or off, and the UI theme (light/dark).

As with any web request, Mixpanel receives your IP address when events are delivered; we do not use it beyond Mixpanel's standard request handling.

We do **not** collect your email address, your Figma account ID, or any content from your design files.

## Who processes this data

Mixpanel, Inc. acts as our data processor. Mixpanel maintains SOC 2 Type II, ISO 27001, and ISO 27701 certifications and offers a GDPR-compliant Data Processing Addendum ([details](https://mixpanel.com/legal/mixpanel-gdpr/)). Data is stored in Mixpanel's United States data centers.

Only the plugin developer has access to this data. We do not sell it, share it with anyone else, or use it for advertising.

## Retention and deletion

- Display name and avatar are deleted from Mixpanel after **24 months of inactivity** (no plugin usage).
- You can request deletion of all data associated with you at any time by contacting us (see below) with your Figma display name. Requests are processed within 30 days.
- Usage events are retained only for product analytics purposes.

## Your rights

Depending on where you live (e.g. GDPR in the EU, PDPA in Taiwan), you may have the right to access, correct, or delete your personal data. Contact us and we will honor these requests regardless of your location.

## Changes to this policy

If the plugin's data collection changes, this document will be updated along with the effective date, and material changes will be noted in the plugin's release notes.

## Contact

- Email: chloehungtaiwan@gmail.com
- Bug reports: https://forms.gle/uFNw9NWSBz4fbp5t6
