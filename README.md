# Formal verification of EVM smart contracts

I audit smart contracts on the EVM with my own private formal prover, **pevm** (poslednaya-evm).  

Tools like **pevm**, **Certora**, **KEVM** use different models of EVM internals, simplifications, assumptions.  
The goal is to achieve complementary verification coverage and perform more thorough smart contract analysis.  

Telegram: @poslednaya_eth  


# Public Findings

**7 public findings: 4 High, 3 Medium | 3 protocols | 2 platforms**

Auditor profiles: [code4rena](https://code4rena.com/@poslednaya) | [sherlock](https://audits.sherlock.xyz/watson/poslednaya)  

| Date | Project | Type | Chain | Engagement | Findings |
| --- | --- | --- | --- | --- | --- |
| 2024 Apr–May | [NOYA](https://github.com/code-423n4/2024-04-noya) | Yield Aggregator | EVM | [Code4rena](https://github.com/code-423n4/2024-04-noya-findings) | [H-04](https://github.com/code-423n4/2024-04-noya-findings/issues/1426) · [M-09](https://github.com/code-423n4/2024-04-noya-findings/issues/1488) · [M-44](https://github.com/code-423n4/2024-04-noya-findings/issues/854) |
| 2024 Apr | [DYAD](https://github.com/code-423n4/2024-04-dyad) | Stablecoin | EVM | [Code4rena](https://github.com/code-423n4/2024-04-dyad-findings) | [H-01](https://github.com/code-423n4/2024-04-dyad-findings/issues/1133) · [H-03](https://github.com/code-423n4/2024-04-dyad-findings/issues/1001) |
| 2024 Mar | [Axis Finance](https://github.com/sherlock-audit/2024-03-axis-finance) | Auction Protocol | EVM | [Sherlock](https://github.com/sherlock-audit/2024-03-axis-finance-judging) | [High](https://github.com/sherlock-audit/2024-03-axis-finance-judging/issues/53) · [Medium](https://github.com/sherlock-audit/2024-03-axis-finance-judging/issues/241) |


# Corpus for **pevm**

Security Case Studies to implement in **pevm**. 
Independent analysis of **published third-party EVM/Solidity findings**. These are research notes, not vulnerabilities originally discovered by me.

| Protocol | Focus | Selected cases | Original report |
| --- | --- | --- | --- |
| [Metric OMM](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2026-07-metric-omm) | Oracle-based DEX / AMM | 5 | [Sherlock](https://audits.sherlock.xyz/contests/1279) |
| [Olas](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2026-05-olas) | Oracle / Protocol-owned Liquidity | 3 | [Code4rena](https://code4rena.com/reports/2026-01-olas) |
| [SukukFi](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2026-04-sukukfi) | Async Vault / ERC-7575 | 3 | [Code4rena](https://code4rena.com/reports/2025-11-sukukfi) |
| [Panoptic: Next Core](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2026-03-panoptic-next-core) | Options / Lending | 3 | [Code4rena](https://code4rena.com/reports/2025-12-panoptic-next-core) |
| [Recall](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2026-03-recall) | Cross-chain / IPC (Solidity) | 3 | [Code4rena](https://code4rena.com/reports/2025-02-recall) |
| [GTE Spot CLOB and Router](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2026-02-gte-clob) | Spot DEX / Order Book | 3 | [Code4rena](https://code4rena.com/reports/2025-07-gte-spot-clob-and-router) |
| [Monolith Stablecoin Factory](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2025-12-monolith-stablecoin) | Stablecoin / Lending | 4 | [Sherlock](https://audits.sherlock.xyz/contests/1212) |
| [Centrifuge Protocol V3.1](https://github.com/poslednaya/smart-contract-security-cases/tree/main/case-studies/2025-11-centrifuge-v3-1) | RWA / Cross-chain | 3 | [Sherlock](https://audits.sherlock.xyz/contests/1028) |

**15 EVM projects / 40 case studies** in the [full research collection](https://github.com/poslednaya/smart-contract-security-cases).
