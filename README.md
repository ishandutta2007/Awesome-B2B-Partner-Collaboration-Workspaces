# Awesome-B2B-Partner-Collaboration-Workspaces

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.

I also have to flag what the search results actually support, because **your list mixes shared channels inside existing SaaS tools with standalone client portal products**, and several entries have no usable pricing.

## The category problem

Your list combines three different things:

- **Shared channels inside collaboration platforms** (Slack Connect, Teams Shared Channels, Asana Guests, Notion Teamspaces, Postman Partner Workspaces)—the "workspace" is a feature of the parent tool, not a standalone product.
- **Client portal / virtual data room products** (Clinked, ClientPoint, Box Hubs)—these are purpose-built external collaboration spaces.
- **Highspot** is a sales enablement platform where external sharing is a feature (Digital Rooms, Pitch), not the core product .
- **Microsoft Copilot** is an AI assistant, not a B2B partner collaboration workspace . Remove it.

## What the search results actually contain

**Shared channel features (proprietary, no standalone price):**

| Platform | What the "workspace" actually is | Pricing status |
|---|---|---|
| **Postman Partner Workspaces** | Enterprise-only feature; team-to-team SSO from May 2025; multi-partner mode for scaling  | **Requires Postman Enterprise plan**; no standalone price surfaced |
| **Slack Connect** | Shared channel connecting up to **250 organizations**; apps must handle cross-workspace authorization  | Not a standalone product; included with Slack plans |
| **Teams Shared Channels** | B2B direct connect; **Entra ID Free is sufficient**; no special license required  | No separate license; included with Teams |
| **Asana External Guests** | **Guests are not free**—contractors need paid seats at the same rate as full users ($10.99–$30.49/mo)  | Guest seats cost the same as team seats |
| **Notion Teamspaces** | Access settings: Open, Closed, or **Private (Business/Enterprise only)**; invite links available  | Not a standalone product; included with Notion plans |

**Client portal products (proprietary, verified pricing):**

| Platform | Pricing | Verified detail |
|---|---|---|
| **Clinked** | **$239/month** (100 members, 1 TB); **$479/month** (3 TB, white-label, 2FA); **VDR from $599/month** (250+ members, redaction, watermarking, NDAs)  | Client portals and virtual data rooms |
| **ClientPoint** | **From $83.00/month** per Software Advice  | Directory listing, not vendor-published |

**No pricing surfaced for:** Box Hubs (Enterprise/Enterprise Plus plans only) , Highspot (quote-only) , or Copilot (usage-based billing "evolving") .

## Open-source: what actually exists

**MemberJunction BizApps Collaboration** is the only open-source project surfaced: it is a **Collaboration Portal** that runs inside a MemberJunction host, with "spaces" defined as data (vocabulary, bands, join mode, settings are metadata), **magic link invites** for outsiders, and **audience-aware AI** (the assistant's access depends on who will see the answer, not who is asking) .

**MemberJunction is an enterprise application platform, not a standalone portal.** You must install it on a MemberJunction host (SQL Server, MemberJunction >=6.1.2, with BizApps Common and Tasks) . **Do not present it as a replacement for Clinked or ClientPoint.**

**No star count surfaced.** Do not invent one.

## What I recommend

**Split into three honest categories:**

**1. Shared Channels in Collaboration Platforms** (features, not standalone products):
- **Postman Partner Workspaces** — Enterprise plan required 
- **Slack Connect** — included with Slack; up to 250 orgs 
- **Teams Shared Channels** — Entra ID Free sufficient 
- **Asana External Guests** — guests pay full seat price 
- **Notion Teamspaces** — Private requires Business/Enterprise 

**2. Client Portal & VDR Products** (proprietary):
- **Clinked** — $239–$599/month 
- **ClientPoint** — from $83/month (directory) 
- **Box Hubs** — Enterprise/Enterprise Plus only 
- **Highspot** — quote-only; external sharing is a feature 

**3. Open-Source**:
- **MemberJunction BizApps Collaboration** — requires MemberJunction host 

**Remove Microsoft Copilot**—it is an AI assistant, not a partner collaboration workspace .

**Flag the Asana guest pricing trap explicitly:** external guests are **not free**—they cost the same as full seats ($10.99–$30.49/month) . This is materially different from Teams Shared Channels, where no additional license is needed .

If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not present Postman or Slack features as standalone products, fabricate Clinked or ClientPoint vendor pricing, or claim MemberJunction replaces a commercial client portal.
