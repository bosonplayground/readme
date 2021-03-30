# Description

The project enables anyone to mint special tokens ('Commitment Tokens') for sending to Pool Together pools, in order to gift real-world items!

We have adapted Boson Protocol's smart contracts for this demo...

We demo how users can mint ERC721 "BSV" tokens.

We demo how users can redeem their physical item prize when they have won a BSV token and have it in their wallet - this updates the token's state and triggers despatch.

We went on to build our own custom pool using a new ERC20 token $BOSONX, modelled on $BOSON (soon to be available!)

# How It's Made

* An ERC20 contract for BosonX token.
* A suite of contracts (draft of Boson Protocol) to manage the Boson NFT contract (ECR1155/ERC721)
** the Boson Protocol mechanism create a ERC1155 Voucher Set for each seller that would like to create an offer,
** then, a buyer will mint a ERC721 NFT from this set when passing an order for that offer
* A UI (clone from PoolTogether UI)
* Some scripts to create offer, mint Boson NFT and transfer to the pool: these scripts allowed us to create an offer (Voucher Set), to order an item from it (mint a NFT ERC721) and transfer this NFT to the pool as a gift for the winner

# Demo

[video](https://www.youtube.com/watch?v=M097G9ey1mI)
