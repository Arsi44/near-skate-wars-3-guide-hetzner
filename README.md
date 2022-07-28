# near-skate-wars-3-guide-hetzner
Near Stake-Wars on Hetzner guide

1) server preparation
Create Srever on Hetzner (You will have to install additional volume)
I use cpx41 (+240Gb volume)

You have to do next steps:
- mount Ubuntu 20.04 ISO 
- restart Server and Install Ubuntu
- during installation create LVM
(example: https://www.youtube.com/watch?v=9Q7hUi1RAVs&ab_channel=HitorikiBatosai)

2) Create your Shardnet wallet and Setup a validator and sync it to the actual state of the network.
You cahe to install nearcore step bu step by next links:
1. https://github.com/near/stakewars-iii/blob/main/challenges/001.md
2. https://github.com/near/stakewars-iii/blob/main/challenges/002.md


3) Deploy a new staking pool for your validator.
https://github.com/near/stakewars-iii/blob/main/challenges/003.md

4) Setup tools for monitoring node status.
Take an experiment with your validator from accourding to this:
https://docs.near.org/api/rpc/introduction
