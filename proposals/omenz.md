# OMENZ Agent Tools

## Basic details
- **Project name:** OMENZ Agent Tools
- **Description:** 74 small, tested pay-per-call tools for AI agents, paid in USDC on Base over x402 v2. Highlights: Authorize (APPROVE/REVIEW/DECLINE + a signed code before paying any x402 endpoint), Uptime Watch (30-day monitoring of a paid endpoint's status, price and payTo), tx preflight, lockers, receipts, handoffs, local business facts, x402 market data.
- **Type:** API
- **Official website:** https://www.omenz.org
- **Logo URL:** https://www.omenz.org/omenz-logo.png
- **Documentation:** https://www.omenz.org/llms.txt (OpenAPI: https://www.omenz.org/api/tollbooth/openapi.json)
- **Public support channel:** hello@omenz.org

## Networks and activity
- **Supported networks:** Base mainnet (eip155:8453)
- **Receiving address:** 0x1bd3aaa92243e3d4352bdce07050aec6fcf5e840

## Payments
- **Paid endpoint + method:** POST https://www.omenz.org/api/tollbooth/v1/authorize ($0.001); full route list in the OpenAPI spec
- **Facilitator:** Coinbase CDP
- **Payment scheme + version:** exact, x402 v2 (`PAYMENT-REQUIRED` header, bazaar extension)
- **Token:** USDC 0x833589fCD6eDb6E08f4c7C32D4f71b54bdA02913 (6 decimals)
- **Successful transaction:** first settled payment to the receiving address on 2026-11-16 (visible on Basescan for 0x1bd3…e840)

## Website application
- Also submitted to payapi.market (2026-11-15).
