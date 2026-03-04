<div align="center">

# VerifyBot
**Verification & trust tooling for Discord**  
A project by **Afterparty Bot Labs**

<a href="https://discord.com/api/oauth2/authorize?client_id=1325944440778657873&permissions=8&scope=applications.commands+bot">
  <img src="https://img.shields.io/badge/Invite%20Bot-Add%20to%20Server-4E8ED8?style=for-the-badge&logo=discord&logoColor=white" alt="Invite VerifyBot" />
</a>
<a href="https://discord.com/invite/BusuZp2G8w">
  <img src="https://img.shields.io/badge/Support-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Support Server" />
</a>
<a href="https://afterpartylabs.xyz">
  <img src="https://img.shields.io/badge/Afterparty%20Bot%20Labs-Website-4E8ED8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Afterparty Bot Labs Website" />
</a>

</div>

---

## What VerifyBot Does

**VerifyBot** helps servers manage verification and trust workflows, with tools for:
- Verification roles (manual + reaction-based)
- Verification logging (channel + webhook)
- Cross-server verification checks (trusted server network)
- Moderation utilities for verified/banned users
- Developer/admin diagnostics (restricted)

---

## Quick Start

1. Invite the bot to your server:  
   **Invite link:**  
   https://discord.com/api/oauth2/authorize?client_id=1325944440778657873&permissions=8&scope=applications.commands+bot

2. Configure logging:  
   - `/setlogs` to set log channel and/or webhook

3. Configure verification:
   - `/addverifyrole` to whitelist roles VerifyBot is allowed to assign/update
   - Optional: `/setreactionverify` to enable reaction-based verification
   - Use `/verify` for manual verification

---

## Commands

### Verification
- `/verify` — Manually verify a user with a role.
- `/setreactionverify` — Set up reaction-based verification: choose a channel, role, and emoji.
- `/addverifyrole` — Whitelist one or more roles for verification updates.
- `/removeverifyrole` — Remove a role from the whitelist.
- `/listverifyroles` — List all roles whitelisted for verification.

### Moderation
- `/check` — Check a user
- `/crosscheck` — Check if a user is verified in other servers.
- `/bancheck` — Check a banned verified user
- `/fullscan` — Perform a retro-active full scan to assign or log a specific whitelisted role.

### Settings
- `/setlogs` — Configure logging settings (channel and/or webhook).

### Info
- `/help` — Show categories and commands for VerifyBot.
- `/about` — Show information about the bot.
- `/ping` — Check the bot
- `/stats` — View verification statistics
- `/support` — Get links to support the bot

> Some commands are restricted to bot developers/owners.

---

## Project Notice

- This bot is **private**
- Forks and PRs are **not accepted**
- Self-hosting is **not supported**

---

*Powered by Afterparty Bot Labs © 2026*
