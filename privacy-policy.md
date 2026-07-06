# Privacy Policy — Bulk V2 Inspector

**Last updated: July 6, 2026**

Bulk V2 Inspector is a Chrome extension that lets you monitor Salesforce Bulk API 2.0 jobs in your own Salesforce org. This policy explains what data the extension accesses and how it is handled.

## What the extension accesses

- **Salesforce session cookie ("sid")**: The extension reads the session cookie for Salesforce orgs you are already logged into in your browser. This session ID is used solely to authenticate API requests to your own Salesforce instance so the extension can retrieve Bulk API 2.0 job information (job status, record counts, and result files).
- **Local preferences**: The extension stores your preferences (such as the Salesforce instance URL you entered and display settings) locally in your browser using Chrome's storage API.

## What the extension does NOT do

- It does **not** collect, store, or transmit your data to the developer or any third party.
- It does **not** send any information to any server other than your own Salesforce instance.
- It does **not** use analytics, tracking, or advertising of any kind.
- It does **not** access cookies from any non-Salesforce website.
- It does **not** store your Salesforce session ID, credentials, or record data. Session cookies are read on demand and used only for the duration of each API request.

## Data flow

All communication happens directly between your browser and your own Salesforce instance (`*.salesforce.com`) over HTTPS. Job result files you choose to download are saved directly to your computer at your explicit request and are never uploaded anywhere.

## Your control

You can remove all locally stored preferences at any time by uninstalling the extension. Your Salesforce session is managed entirely by Salesforce; logging out of Salesforce immediately revokes the session the extension relies on.

## Changes to this policy

Any changes to this policy will be posted at this URL with an updated date.

## Contact

If you have questions about this policy or the extension, contact: **[your-email@example.com]**
