---
layout: default
title: VerifyBot
description: Official documentation and command reference for VerifyBot by Afterparty Bot Labs.
---

---

## What VerifyBot Does

**VerifyBot** helps servers manage verification and trust workflows with tools for:

- Verification roles (manual + reaction-based)
- Verification logging (channel + webhook)
- Cross-server verification checks (trusted server network)
- Moderation utilities for verified/banned users
- Developer/admin diagnostics (restricted)

---

## Quick Start

### 1. Invite the bot to your server

[![Add VerifyBot](https://img.shields.io/badge/Add%20VerifyBot-Invite-4E8ED8?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/oauth2/authorize?client_id=1325944440778657873&permissions=2953309377&integration_type=0&scope=bot+applications.commands)

### 2. Configure logging

`/setlogs` — set log channel and/or webhook

### 3. Configure verification

`/addverifyrole` — whitelist roles VerifyBot can assign  
`/setreactionverify` — enable reaction-based verification  
`/verify` — manually verify a user

---

## Commands

### Verification

`/verify` — Manually verify a user with a role  
`/setreactionverify` — Set up reaction-based verification (channel, role, emoji)  
`/addverifyrole` — Whitelist roles for verification updates  
`/removeverifyrole` — Remove a role from the whitelist  
`/listverifyroles` — List all whitelisted verification roles  

### Moderation

`/check` — Check a user  
`/crosscheck` — Check if a user is verified in other servers  
`/bancheck` — Check a banned verified user  
`/fullscan` — Perform a retroactive full scan to assign or log a whitelisted role  

### Settings

`/setlogs` — Configure logging settings (channel and/or webhook)

### Info

`/help` — Show command categories  
`/about` — Show information about the bot  
`/ping` — Check bot latency  
`/stats` — View verification statistics  
`/support` — Get support links  

> Some commands are restricted to bot developers or owners.

---

## Project Notice

- This bot is **private**
- Forks and PRs are **not accepted**
- Self-hosting is **not supported**
