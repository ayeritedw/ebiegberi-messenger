# Ebiegberi Messenger — Tokenized Wari Communities on Solana

One Wari, One Voice. 14 Nembe Kingdom Houses, each with its own private home.

## Live Demo
https://ebiegberi.com/wari/

## What it is
In Nembe Kingdom, 14 Chieftaincy Houses (Wari) coordinate everything — funerals, levies, disputes, health — on WhatsApp groups they don't own, with no membership control and no transparent treasury.

Ebiegberi Messenger gives each Wari its own private home. Only approved members can enter.

## Live Wari
- Igbeta (Pilot) — LIVE
- Ockiya — LIVE
- Kulo / Koko — LIVE
- 11 more coming soon

## How it works
1. User picks a Wari → fills Join Form: Name, Phone, Compound, Location (Nembe City / Bassambiri / Port Harcourt / Yenagoa / Lagos / Abuja / Diaspora)
2. Request saves to Supabase `join_requests` + WhatsApp to Secretary
3. Secretary / Head Chief approves
4. Member connects Phantom wallet → Wari Membership Token minted on Solana Devnet
5. Token holder can access private chat. Treasury: dues in SOL/USDC, 2-of-2 approval (Head Chief + Secretary)

## Solana (Devnet)
Connect Phantom wallet on Join Form. Membership = SPL Token. Treasury = 2-of-2 approval.

## Stack
HTML/CSS/JS + Supabase (Postgres + Realtime) + Solana Web3.js

## Database
- `messages (wari_id, sender_name, message)`
- `announcements`
- `join_requests (wari_id, full_name, phone, compound, location)`

## How to Run
Open `wari/igbeta/index.html` in browser. No build needed.

## Team
Diepiriye Wayne Ayerite — DEVLOG TECHNOLOGIES LIMITED
