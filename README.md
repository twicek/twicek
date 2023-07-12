# Hi! twicek here 👋

8 months ago I started my journey as a security researcher focusing primarily on smart contract written in Solidity/Vyper. During my journey, I participated in audit contests on [code4rena](https://code4rena.com/) and [Sherlock](https://app.sherlock.xyz/audits/contests) where I learned a lot and found multiple vulnerabilities. I also tried my hands at [Immunefi](https://immunefi.com/), and while learning to interact with deployed contract using foundry I found two additional vulnerabilities on already audited contracts.

I'm currently available for work as a solo auditor, you can reach me at [twiceksec@gmail.com](mailto:twiceksec@gmail.com) or DM me on Twitter [@twicek_k](https://twitter.com/twicek_k) for informations and fill this [form](https://forms.gle/RECdxmQ8AtTCQCVh7) to get a quote.

You can find examples of previous auditing work below.


# Security contributions

## Immunefi
| Project | Findings | Severity |
|----------|----------|----------|
| Undisclosed | Griefing | Medium |
| Undisclosed | Uninitialized critical variable | Low 

## Some contest findings

| Contest | Findings |
|----------|----------|
|   Union Finance V2 (First) |   1. [UserManager.updateFrozenInfo cannot be called from UToken](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/41)   |
|   Union Finance V2 (Second) |   1. [cancelVouch doesn't update the voucher index of the last vouch of a borrower properly](https://github.com/sherlock-audit/2023-02-union-judging/issues/31) (2nd place)   | 
|   OpenQ |   1. [Funders can deny rewards to last claimants by calling refundDeposit between tiers claims](https://github.com/sherlock-audit/2023-02-openq-judging/issues/64)<br>2. [refundDeposit function can be DoS by an unbounded loop in getLockedFunds](https://github.com/sherlock-audit/2023-02-openq-judging/issues/32)   |
|   Fair funding (Vyper) |   1. [The auction can be started by anyone calling settle before start_auction is called by the owner](https://github.com/sherlock-audit/2023-02-fair-funding-judging/issues/74)   |
|   Opyn |   1. [Anyone in the order queue wanting to withdraw or deposit can grief the auction by making withdrawAuction or depositAuction always revert](https://github.com/sherlock-audit/2022-11-opyn-judging/issues/73)   |
|   Y2K |   1. [ownerToRollOverQueueIndex is incorrectly updated when a user call enlistInRollover twice](https://github.com/sherlock-audit/2023-03-Y2K-judging/issues/60)<br>2. [Increasing the relayerFee create a risk for relayers](https://github.com/sherlock-audit/2023-03-Y2K-judging/issues/62)<br>3. [After having roll over once a user will not be able to roll over again](https://github.com/sherlock-audit/2023-03-Y2K-judging/issues/61)<br>4. [Queued deposits can get stuck indefinitely in the deposit queue](https://github.com/sherlock-audit/2023-03-Y2K-judging/issues/63)   |
|   Redacted Cartel   |  1. [A malicious early user/attacker can manipulate the pxGmx's pricePerShare to take an unfair share of future user's deposits](https://github.com/code-423n4/2022-11-redactedcartel-findings/issues/407)  |
|  Escher  | 1. [Users can lose funds if they call buy with _amount larger than type(uint48).max](https://github.com/code-423n4/2022-12-escher-findings/issues/512)<br>2. [If very few NFTs have been sold saleReceiver will have to buy all remaining NFT to retrieve the contract funds](https://github.com/code-423n4/2022-12-escher-findings/issues/528)

# Open source contributions
- Development contributions using foundry: [hyperlane-fork-testing](https://github.com/twicek/hyperlane-fork-testing)
