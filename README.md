# Bulk V2 Inspector

**The missing monitoring UI for Salesforce Bulk API 2.0 — a Chrome extension.**

Salesforce's built-in Bulk Data Load Jobs page shows limited detail for Bulk API 2.0 jobs — no batch information and minimal visibility into what's actually happening. Bulk V2 Inspector fills that gap with a dedicated dashboard for inspecting your org's Bulk API 2.0 ingest and query jobs.

<!-- Once published, add your Chrome Web Store badge/link here:
[Install from the Chrome Web Store](https://chromewebstore.google.com/detail/YOUR_EXTENSION_ID)
-->

## Features

- ⚡ **View all Bulk API 2.0 jobs** in your org — ingest and query — with live status
- 📊 **See records processed and failed** at a glance, with per-job detail
- 🔍 **Filter and search** by job type (Query, Query All, Insert, Update, Upsert, Delete, Hard Delete) or paste a job ID
- ⬇️ **Download job results as CSV** — successful, failed, and unprocessed records — in one click
- 🔐 **No OAuth setup, no connected app** — uses your existing Salesforce browser session
- 🎨 SLDS-inspired theme so it feels at home next to Salesforce

## Who it's for

Salesforce admins, developers, and data teams running large data loads through Data Loader, integration middleware, or custom Bulk API 2.0 clients — anyone who needs to answer *"did my job finish, and what failed?"* without clicking through Setup.

## Getting started

1. Install the extension from the Chrome Web Store
2. Log in to your Salesforce org in Chrome
3. Click the Bulk V2 Inspector icon in your toolbar
4. Select or enter your instance URL (e.g., `yourdomain.my.salesforce.com`) and click **Load Jobs**

## Privacy

All requests go directly from your browser to your own Salesforce instance. Nothing is stored or transmitted to any third-party server — no analytics, no tracking, no data collection.

See the full [Privacy Policy](./privacy-policy.md).

## Permissions explained

| Permission | Why it's needed |
|---|---|
| `cookies` | Reads your Salesforce session cookie (`sid`) to authenticate Bulk API 2.0 requests to your own org |
| `storage` | Saves your instance URL and display preferences locally |
| `downloads` | Saves job result CSV files to your computer when you click download |
| `https://*.salesforce.com/*` | All API calls go exclusively to your own Salesforce instance |

## Support

Found a bug or have a feature request? [Open an issue](../../issues) in this repository.

---

*Bulk V2 Inspector is an independent project and is not affiliated with or endorsed by Salesforce, Inc.*
