I audit DeFi smart contracts on the EVM with my own private formal prover, `poslednaya` (work in progress). 
`poslednaya` works on bytecode lvl, uses symbolic execution, model checking, and SMT solvers to verify bytecode level of smart contracts.

`poslednaya`, Certora, KEVM use different models of EVM internals, simplifications, assumptions. 

The goal is to achieve complementary verification coverage and perform more thorough smart contract analysis.

Telegram: @poslednaya_eth

## Security Research Track Record

**7 public findings: 4 High, 3 Medium | 3 protocols | 2 platforms**

| Date | Project | Type | Chain | Engagement | Findings |
| --- | --- | --- | --- | --- | --- |
| 2024 Apr–May | [NOYA](https://github.com/code-423n4/2024-04-noya) | Yield Aggregator | EVM | [Code4rena](https://github.com/code-423n4/2024-04-noya-findings) | [H-04](https://github.com/code-423n4/2024-04-noya-findings/issues/1426) · [M-09](https://github.com/code-423n4/2024-04-noya-findings/issues/1488) · [M-44](https://github.com/code-423n4/2024-04-noya-findings/issues/854) |
| 2024 Apr | [DYAD](https://github.com/code-423n4/2024-04-dyad) | Stablecoin | EVM | [Code4rena](https://github.com/code-423n4/2024-04-dyad-findings) | [H-01](https://github.com/code-423n4/2024-04-dyad-findings/issues/1133) · [H-03](https://github.com/code-423n4/2024-04-dyad-findings/issues/1001) |
| 2024 Mar | [Axis Finance](https://github.com/sherlock-audit/2024-03-axis-finance) | Auction Protocol | EVM | [Sherlock](https://github.com/sherlock-audit/2024-03-axis-finance-judging) | [High](https://github.com/sherlock-audit/2024-03-axis-finance-judging/issues/53) · [Medium](https://github.com/sherlock-audit/2024-03-axis-finance-judging/issues/241) |


1. Current Work

poslednaya — private EVM prover, WIP. Здесь ты рассказываешь о symbolic execution, SMT и альтернативных моделях memory/storage.
