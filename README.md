# Hubster

[Submitted for the EthGlobal hackathon of September 2022]

## Description

Hubster is a web3 LinkedIn. The logic is as follows:

1. People get a proof-of-humanity verification through Worldcoin
1. They can mint an unique, editable, profile NFT.
1. They can then self-certify their previous experiences (as on Linkedin) through other NFTs.
1. Visitors can search for profiles and visit them.
   The next step would be to use XMTP to message them.

## Tech stack

The dApp leverages Worlcoin, Polygon, NFTPort and IPFS.

The full tech stack comprises

- for the dApp part (in `/smart-contract`), hardhat, ERC721.
- for the website (in `/front-end`), Vercel/Next/React along with Rainbowkit/wagmi.
