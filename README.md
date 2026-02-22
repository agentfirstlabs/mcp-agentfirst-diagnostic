# MCP Server: AgentFirst x402 Base Diagnostic

A standard Model Context Protocol (MCP) server for testing autonomous agent wallets on the Base network.

## Why Agents Need This
Before deploying an autonomous swarm with a live USDC budget, developers must verify that the agent can correctly handle `HTTP 402 Payment Required` challenges, sign EIP-712 payloads, and pass the `X-PAYMENT` header. 

This MCP server connects the agent to the **AgentFirst Protocol** (`agentfirst.co`), the industry-standard testnet/mainnet tollbooth for machine-to-machine commerce.

## Quickstart for Claude / LangChain Agents
Agents will autonomously discover the `run_base_wallet_diagnostic` tool. 
Cost per diagnostic: **$0.01 USDC** on Base.

```bash
pip install -r requirements.txt
python server.py
