# Tab Curfew Privacy Policy

**Last updated:** 23/10/2026

Tab Curfew is a browser extension that closes tabs you have not used for a chosen period and keeps
a local list of the tabs it closed.

## What the extension handles

To do its job, Tab Curfew reads and stores:

* the URL, title, and favicon of open tabs;
* the time each tab was last active, and (when the "time since opened" clock is selected) when it
was opened;
* the URL, title, site, favicon, last-active time, and close time of tabs it closes;
* your settings, including the time span, allowlist, check interval, and pause state.

The extension does **not** read page content, form fields, passwords, cookies, or keystrokes. It has
no host permissions and no content scripts.

## Where the data goes

All of this data is stored locally in your browser profile using `chrome.storage.local`. **It is
never transmitted to the developer or to anyone else.** The extension contains no network requests,
no analytics, no advertising, and no third-party SDKs.

## How long it is kept

* The closed-tab list keeps the 200 most recent entries; older entries are discarded.
* Activity timestamps are kept while the tab exists and are pruned when tabs close.
* Settings and the closed-tab list remain until you clear them or uninstall the extension.
* Uninstalling the extension removes its local storage.

## Your controls

* **Clear list** in the popup removes the closed-tab entries without reopening them.
* **Pause 1 hour** stops automatic closing temporarily.
* Disabling or uninstalling the extension stops all processing.
* You can clear extension storage from Chrome's extension details page.

## Sharing

No data is sold, rented, or shared with third parties. There is no data to share because nothing
leaves the device.

## Children

Tab Curfew is a general-purpose utility and is not directed at children.

## Changes

If a future version changes how data is handled, this policy will be updated and the change will be
described in the extension's release notes.

## Contact

Questions about this policy: me@eallie.co.za

