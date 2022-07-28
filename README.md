# Audius Governance Takeover PoC

This is a proof-of-concept exploit for the [vulnerability in an Audius contract](https://blog.audius.co/article/audius-governance-takeover-post-mortem-7-23-22).

This is _not_ an attempt to reproduce the actual exploit transactions ([1](https://etherscan.io/tx/0xfefd829e246002a8fd061eede7501bccb6e244a9aacea0ebceaecef5d877a984), [2](https://etherscan.io/tx/0x4227bca8ed4b8915c7eec0e14ad3748a88c4371d4176e716e8007249b9980dc9)).

This is just an alternative, more simplified version of the attack, built for educational purposes.

## Requirements

- [Foundry](https://book.getfoundry.sh/)

## Run

1. Fill the `script/Constants.sol` file with your preferred RPC URL to fork.
2. Run script:

```
$ forge script script/Script.s.sol:AttackerScript
```
