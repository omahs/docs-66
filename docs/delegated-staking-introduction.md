# Delegated Staking

Forta node runners set up scan nodes and register nodes in pools of their own. While they are required to deposit stake to signal the reliable pools and earn rewards, others can delegate their FORT tokens to these pools and generate rewards for themselves.

By delegating FORT tokens, participants are increasing the security and reliability of the network, having more skin in the game, signaling the best and most reliable Forta Scanner Pools and helping them get incentivized.

In exchange of the delegated stake, pool owners share their rewards with delegators by setting up

- how much of the delegated stake should allocated,
- what percentage of delegators' rewards should be withheld as commission.

After every reward epoch ends, rewards in FORT are assigned to the pools in the reward distribution smart contract, at the earliest convenience. This smart contract decides how to distribute the rewards between owners and delegators.

To learn more about rewards, visit the [Rewards Formula page](delegated-staking-rewards.md).

In accordance with Forta Network's mission of securing Web3, delegated stakes are subject to the possibility of a small partial reduction in case the pool they are delegating to is slashed (either because of technical reasons or misconduct).

Delegators are subject to a waiting period of 10 days to reclaim their FORT after initiating a stake withdrawal.

# Choosing a Scanner Pool

Making a more careful choice can help you generate more rewards. There are several things to consider before delegating stake to a pool:

- **SLA (uptime) score of the pool's scanners:** Bad score means low rewards.
- **Commission:** What percentage of delegator rewards is withheld by the pool owner
- **Available stake allocation capacity:** Unallocated stake does not generate rewards.
- **Communication with delegators in Forta Discord server**