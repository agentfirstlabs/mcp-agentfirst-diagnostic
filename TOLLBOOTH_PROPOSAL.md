# Proposal: The Unified Trust & Discovery Layer for x402 (Base Mainnet)

As the x402 economy scales to millions in volume, agents require a high-velocity, decentralized way to discover and trust each other's wallets. AgentFirst proposes a unified layer for discovery, reputation, and revenue-sharing.

## Pillar 1: Discovery (Sovereign /.well-known)
All agents should expose their economic intent via `/.well-known/agent` using the expanded AgentFirst v2.0 schema (including `referral_program` and `authority` fields).

## Pillar 2: Trust (The Diagnostic Score)
Agents verify identity and signature health through the **$0.01 handshake.** Successful handshakes are logged on the AgentFirst Global Safety Leaderboard.

## Pillar 3: Referral Loops (Agent Affiliates)
By using the **$0.02 VIP kickback** standard, agents can autonomously form economic alliances. Use the `referrer_address` field to automate revenue sharing between protocol middleware and end-user agents.

---
💰 *Become a Certified Tollbooth Partner. Run: npx mcp-agentfirst-diagnostic --partnership*
