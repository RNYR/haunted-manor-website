---
layout: default
title: Privacy Information
---

# Haunted Manor Bot — Privacy Information

**Last updated:** October 15, 2026  
**Operator (person responsible for this bot):** RNYR  
**Contact:** `v4rdr` on Discord

## 1. Scope

Haunted Manor Bot (the **Bot**) is used **exclusively for a private, non-commercial murder mystery game involving approximately 20 friends on one private Discord server**. This page explains how the game uses participant data. The Bot is not offered to the public.

## 2. What information is used

To run the game, the Bot uses:

- **Discord user IDs** to recognize players and enforce one roll per account.
- **Three assigned character traits per player**, linked to those IDs, so the same traits can be retrieved later and not allocated to someone else.
- **The configured Discord server ID** to restrict the Bot to the intended server.

The Bot does not ask players for real names, email addresses, passwords, payment details, or ordinary chat messages. Discord and the hosting provider may process their own technical information under their own policies.

## 3. Why this information is used

Information is used only to assign, remember, and retrieve traits, prevent repeat rolls and overlapping assignments, and help troubleshoot operation during the event. It is **not sold, used for advertising, or shared with other players by the Bot**.

## 4. Private social use and GDPR

This is a private activity among friends, not a public or commercial service. The **personal or household activity exception** in Article 2(2)(c) of the GDPR **may** apply to processing undertaken purely for this private activity. Whether it applies depends on how the Bot is actually operated; it is **not a blanket exemption** merely because the server is private. If the Bot becomes publicly available or its use expands beyond this personal game, its privacy practices and legal obligations will be reviewed, including any applicable legal basis under GDPR.

## 5. Where data is stored and who can see it

Trait definitions and player assignments are handled by the Bot's JSON-based storage. The live data is stored in the Bot's hosting environment (currently intended for Railway); the operator and anyone with authorized infrastructure access may be able to view it.

`/roll` and `/mytraits` use **ephemeral Discord responses** visible to the requesting player within Discord, not public channel messages. This does **not** mean that stored assignments are inaccessible to the operator or infrastructure providers. Players can also choose to tell others their traits.

Do not put the live database, assigned traits tied to Discord IDs, or the Discord bot token in a public GitHub repository.

## 6. Services involved

The game runs through [Discord](https://discord.com/privacy) and is hosted using [Railway](https://railway.com/legal/privacy). Both may handle technical data according to their own terms and policies. We do not sell player information.

## 7. How long data is kept

The operator will **manually delete the saved player assignments within 30 days after the murder mystery event ends**, or earlier upon a verified request where appropriate. The current Bot does **not** automatically delete assignments on a timer. Removing an assignment means `/mytraits` can no longer recover the old result. Trait definitions without player links may be retained for future games.

## 8. Questions, access, and deletion

To ask what assignment is stored for your account, or to request deletion, contact **`v4rdr` on Discord**. The operator may verify that the request comes from the account concerned before sharing or deleting information. Requests will be handled reasonably and in accordance with any applicable legal requirements.

If data-protection law applies, participants may have additional statutory rights, including access, erasure, objection, and the right to contact a supervisory authority. In Czechia, that authority is [ÚOOÚ](https://uoou.gov.cz/en).

## 9. Security and changes

The operator intends to restrict access to the bot's data and keep credentials private. No service can promise absolute security. This page will be updated if the game changes materially or the Bot is used beyond the private friend group.

*Haunted Manor Bot is independent and is not affiliated with Discord Inc.*
