---
id: BeforeYouStart
title:  Before you start
sidebar_label: Before you start
---

Warnings about the dangers of running eth2 nodes are in [Recommendations.md](../Support/Recommendations.md).
In particular, you must be sure to secure your seed phrase, the mnemonic. Without it, your
staked funds *cannot* be withdrawn.

You may also want to take a look at a [guide to Linux host security](https://www.coincashew.com/coins/overview-eth/guide-or-security-best-practices-for-a-eth2-validator-beaconchain-node#setup-two-factor-authentication-for-ssh-optional).

1. Install prerequisites
2. Choose a client and do initial setup.
3. Build the client
4. Generate deposit files and an eth2 wallet. This can be done within this project, or outside of it
5. Import the validator keystore files generated in the previous step
6. Run the client
7. Finalize the deposit. This is not done within this project
8. A baseline set of Grafana dashboards are included, see step 8.  Feel free to add more, or submit a PR with your favorite dashboards.
9. Configure your system to start the eth2 node on boot (optional)

## Step 1: Install prerequisites

You will need git, docker, and docker-compose. This should work on Linux, possibly MacOS.
