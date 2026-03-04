<div align="center">

<img src="assets/images/verify-bot.png" width="120">

# VerifyBot
Verification & trust tooling for Discord  
A project by **Afterparty Bot Labs**

</div>

<a href="https://discord.com/oauth2/authorize?client_id=1325944440778657873&permissions=2953309377&integration_type=0&scope=bot+applications.commands">
  <img src="https://img.shields.io/badge/Add%20Bot-Invite-4E8ED8?style=for-the-badge&logo=discord&logoColor=white" alt="Invite VerifyBot" />
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

👉 **[Add VerifyBot to your server](https://discord.com/oauth2/authorize?client_id=1325944440778657873&permissions=2953309377&integration_type=0&scope=bot+applications.commands)**

2. Configure logging:

- `/setlogs` — set log channel and/or webhook

3. Configure verification:

- `/addverifyrole` — whitelist roles VerifyBot can assign
- `/setreactionverify` — enable reaction-based verification
- `/verify` — manually verify a user

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
